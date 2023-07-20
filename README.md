# Intel Image Classification

#### -- Project Status: Completed

## Project Intro/Objective and Description
The purpose of this project is to classify the input image into one of these categories: building, forest, glacier, mountain, sea, or street. Transfer learning has been used with MobileNetV2, which is a convolutional neural network that is 53 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. Training this pre-trained network is a lot faster than training one from scratch. The accuracy was 92.43% (baseline is 50%). Next, I built a website to deploy the model using FastAPI.

Dataset link: https://www.kaggle.com/datasets/puneet6060/intel-image-classification

### Methods Used
* Deep Learning
* Transfer Learning
* Data Visualization
* Model Deployment

### Technologies
* Python
* Jupyter Notebook
* Tensorflow, Numpy, OpenCV, Matplotlib
