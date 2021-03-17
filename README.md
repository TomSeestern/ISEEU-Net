
# The ISEEU-Net Change Detection System

> The Code to my (Tom Segbers) Bachelor Thesis with the topic "**Change Detecion in Shrubland Areas on High Resolution UAV Video**"

> The system has the ability to detect movement from a camera that feeds a image stream into the system.

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

## Installation

- Cone this repo
- Install dependencies
```bash
pip3 install -r requirements.txt
```
- (Optional) You need to have access to my wandb runs to run this system. [ContactMe](mailto:bathesis@tomsegbers.de) 
```bash
wandb login
```
- Ready to rock! Check [Example](##Example) for how to run the system.

---

## Features
## Usage 
For single video inference see [Example](##Example) Chapter

For "Live" inference with streamed video you can extend the "liveInference.py" file. Currently this still uses a static video as input, but this can be swapped for any other input stream like a ffmpeg steram.
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
