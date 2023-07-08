# Pose-Estimation

Pose estimation is a computer vision methodology used
to predict and track the key-points (major joints) of a human figure.


We performed comparative analysis on the prediction results produced by 3 deep learning pose estimation models namely Blazepose,
Keypoint R-CNN and MMPose.They identify the joint keypoints of the
human figure in the input image frame. Comparative analysis is performed by a Gaussian Mixture Model which generates 4 clusters of
the keypoints and calculates their F1 score and accuracy. 

The cummulative accuracy for the 4 clusters in walking pose frame for the
three models respectively are 0.86, 0.67, 0.75. 
