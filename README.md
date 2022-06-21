# Convolutional neural network

## General info
Convolutional neural network to distinguish sunglasses from smartphones using a webcam. The CNN is based on MobileNetV2 with a final binary dense layer.

## Technologies
* Python 3.9.7
* libraries and its versions are listed in requirements.txt and can be installed with:
```
$ conda install --name <environment_name> --file requirements.txt
```

## Setup
1. Make sure that a webcam is attached to your computer

2. Run jupyter notebook and change to the directory imageclassifier/src. Open *Projekt.ipynb*.

3. Execute the last cell of the notebook. Your webcam should then be activated, showing a black frame.

4. Hold sunglasses or a smartphone into the black frame and press *space*. The notebook will tell wether it are sunglasses or a smartphone.

5. To stop the camera press *q*
