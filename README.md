"Yoga-Pose-Detector" 

About the dataset:
Dataset consists of 5 kinds of Yoga poses 
* warrior2 
* tree 
* goddess 
* plank 
* downdog

For detecting the pose and making the skeleton i have used Movenet and stored the joint angles, joint positions  and Yoga pose in an array and converted it into .csv format and used Deep Learning of the .csv file .
Using  Deep Learning and Movenet i have achieved the following best result:

loss: 0.0560 - accuracy: 0.9802 - val_loss: 0.0716 - val_accuracy: 0.9750
