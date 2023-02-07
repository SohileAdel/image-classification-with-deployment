In this problem, the model tries to classify the input image into one of these categories: building, forest, glacier, mountain, sea, and street. transfer learning has been used with MobileNetV2, which is a convolutional neural network that is 53 layers deep. You can load a pretrained version of the network trained on more than a million images from the ImageNet database. The pretrained network can classify images into 1000 object categories, such as keyboard, mouse, pencil, and many animals. Training this pretrained network is a lot faster than training one from scratch. The accuracy after training that model was 92.43%. After that, the model has been deployed using FastApi.

Application Link: https://imageclassification.herokuapp.com/

Dataset link: https://www.kaggle.com/datasets/puneet6060/intel-image-classification
