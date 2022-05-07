# **Advanced Lane Finding**
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)
![Lanes Image](./examples/example_output.jpg)

Overview
---

In this project, the goal is to write a software pipeline to identify the lane boundaries in a video. Advanced Computer Vision techniques like Perspective Transformations and Color Spaces are used.

All the code relevant to the project is contained in [code](./code) folder and the [writeup](./writeup.md) is also present.

The project meets all the requirements mentioned in the [project rubric](https://review.udacity.com/#!/rubrics/571/view)

Getting Started
---

The project has been developed on Windows 10 machine with Python 3.8.8. Download Python and follow the instructions ahead for the installation.

## Prerequistes
Install dependencies

```bash
pip install -r requirements.txt
```

Usage
---

The project consists of python files that are present in the [code](./code) folder. Individual parts of the pipeline can also be run.

To run the main pipeline

```bash
python main.py
```

To run a part of the pipeline

```bash
python camera_calibration.py
python image_transformation.py
python lane_detection.py
```

Output
---

Link to [Youtube Video](https://youtu.be/hrin-qTn4L4)