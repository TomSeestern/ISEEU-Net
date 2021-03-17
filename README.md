
# The ISEEU-Net Change Detection System

> ~~The Code~~ and Docs to my (Tom Segbers) Bachelor Thesis with the topic "**Change Detecion in Shrubland Areas on High Resolution UAV Video**"

> The system has the ability to detect movement from a camera that feeds a image stream into the system.

<sub><sup> Code was removed due to a Company request, resulting Videos and Bachelor Thesis PDF are still available in the [doc](doc) folder </sup></sub>

![Example result of the System](doc/img/example_CD_A3_v11.gif)

---

## Table of Contents (Optional)

> If your `README` has a lot of info, section headers might be nice.

- [Installation](#installation)
- [Features](#features)
- [FAQ](#faq)
- [Support](#support)


---

## Example

```bash
python3 inference <wandbRunPath> <inputVidPath> <pathToTempFolder> 
```
Example: 
```shell
python3 inference.py tomseestern/ChangeDetector/bknulmgz ./test/CD2014_traffic_1_RAW.avi ./temp/
```

System returns the save location of a overlayed video with original vid and predicion combined.

---

## Documentation
See my Thesis for overall system documentation. [BA-Thesis.pdf](doc/Detecting_Change_in_Scrubland_Enviroment.pdf)

---

## FAQ

- ** Can this run on a Nvidia Jetson **
    - Yes just install the dependencies and you should be good to go. Just make sure you have the specific versions installed.

---

## Support

Reach out to me at one of the following places!

- Website at <a href="https://tomsegbers.de" target="_blank">`tomsegbers.de`</a>

---
