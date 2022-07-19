# TensorFlow Lite Helmet Detection Android APP

   Code taken from [this tensorflow repo](https://github.com/tensorflow/examples/tree/master/lite/examples/object_detection/android).

### Overview

This is a camera app that continuously detects persons with and without bicycle helmet (bounding boxes and
classes) in the frames seen by your device's back camera, with the option to use 
[EfficientDet Lite 0](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite0/detection/metadata/1),
[EfficientDet Lite1](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite1/detection/metadata/1),
[EfficientDet Lite2](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite2/detection/metadata/1),
or
[EfficientDet Lite3](https://tfhub.dev/tensorflow/lite-model/efficientdet/lite3/detection/metadata/1)
model trained on the [Kaggle dataset](kaggle.com/datasets/brendan45774/bike-helmets-detection).

This application should be run on a physical Android device.

 <img src="https://user-images.githubusercontent.com/11874274/179691419-20401e67-ad6f-4ee1-8997-b41326c34a73.png" width="400">
 <img src="https://user-images.githubusercontent.com/11874274/179691456-dfb18427-e9fd-44ad-8c30-99e70dc99e9e.png" width="400">
 <img src="https://user-images.githubusercontent.com/11874274/179691612-c52d8cb9-b1d5-4453-83f2-c7ed446a854c.png" width="400">

## Build the demo using Android Studio

### Prerequisites

*   The **[Android Studio](https://developer.android.com/studio/index.html)**
    IDE. This sample has been tested on Android Studio Bumblebee.

*   A physical Android device with a minimum OS version of SDK 24 (Android 7.0 -
    Nougat) with developer mode enabled. The process of enabling developer mode
    may vary by device.

### Building

*   Open Android Studio. From the Welcome screen, select Open an existing
    Android Studio project.

*   From the Open File or Project window that appears, navigate to and select
    the tensorflow-lite/examples/object_detection/android directory. Click OK.

*   If it asks you to do a Gradle Sync, click OK.

*   With your Android device connected to your computer and developer mode
    enabled, click on the green Run arrow in Android Studio.

### Models used

Downloading, extraction, and placing the models into the assets folder is
managed automatically by the download.gradle file.

You can use this pretrained models to test [here](https://drive.google.com/drive/folders/1UcWFlxTBfG2iu0lNmXVqmUIzO1Wp7KiS?usp=sharing).

### Train your model

You can train your own model with this [Jupyter Notebook](https://colab.research.google.com/drive/1_rr9MYLOjJ4GwU9qMsAwJ3LvShllJeW5?usp=sharing) using Google Colaboratory.

### Slides

View some [slides](https://slides.com/danilomendoza/deck-6167ec) about this app.
