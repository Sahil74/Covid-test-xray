# Covid-test-xray
### Overview
Chest X-ray can prospectively predict outcomes for a patient with COVID-19 in high pre-test probability settings or a quick turnaround of RT-PCR testing.

We wanted to know whether chest imaging is accurate enough to diagnose COVID-19 in people with suspected infection.

<p> <img src='https://c.files.bbci.co.uk/5A82/production/_112107132_credit-ucsdhealth.png'></p> 

This project uses a convolutional neural network (CNN) to identify chest X-ray pictures as COVID-19 positive or negative. The splitfolders library divides the dataset into three sets: training, validation, and testing. The model architecture is made up of multiple convolutional and pooling layers, followed by dense layers for classification.

Prerequisites

* Python 3.x
* TensorFlow
* Keras
* Matplotlib
* splitfolders


### Dataset
The dataset for this study consists of chest X-ray pictures classified as COVID-19 positive or negative. It is separated into three subsets: training, validation, and test. The dataset is organised as follows.

