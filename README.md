![Demo](https://github.com/anujsahani01/Yoga-Pose-Detector/assets/83875986/e46b4697-1cd2-4510-9be8-622157035d92)# Yoga Pose Detector

### Used MoveNet(movent thunder) for Pose and Skeleton detection and then using a simple Deep Learnig Model for Classification Purpose

Working of Model:
The whole model is divided into 2 main sub-parts.In the first part for Ultra fast and accurate pose detection model i used tensorflow MoveNet thunder bird which return 17 keypoints(joints) with their corresponding co-ordinates. Then i used kaggle posses dataset used image agumentation to increase the size of my dataset then passed batches of images through the function for calculating angles between joints for different yoga posses and make a .csv file out of it. Then the csv file was used as the dataset for my second model for pose classification purpose.

# About the dataset:

#### Dataset for MoveNet Model
Dataset consists of 5 kinds of Yoga poses 
* warrior2 
* tree 
* goddess 
* plank 
* downdog

#### Dataset for Deep Learning Model
![image](https://github.com/anujsahani01/Yoga-Pose-Detector/assets/83875986/f247afdb-c6e2-47ff-966c-fc1f02812c9a)


### Results
#### Confusion Matrix
![image](https://github.com/anujsahani01/Yoga-Pose-Detector/assets/83875986/d021b282-e756-4535-9416-92d86d6f29b4)

#### Loss and Accuracy
loss: 0.0560 - accuracy: 0.9802 - val_loss: 0.0716 - val_accuracy: 0.9750


# Demo of my model
![Demo](https://github.com/anujsahani01/Yoga-Pose-Detector/assets/83875986/31b14694-501d-4bfe-8e17-eb3f622e7cec)
