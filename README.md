# The Referee's Watch

![](/TRW.JPG)

## Overview
The Referee's Watch project aims to detect and factorize NFL fields and players using advanced computer vision techniques. Field detection is a fundamental task in sports analytics, providing valuable information such as ball possession, player movements, and game events. The proposed approach leverages the Hough transform algorithm to detect field lines effectively, accurately identifying yard lines, end zones, and sidelines.

Player detection poses challenges due to high variability in appearance, pose, and occlusions. To address this, the project employs the state-of-the-art YOLOv8 model for player detection. Field mark detection is also crucial for sports analytics, providing information on the position and orientation of the ball and players. For this task, the project uses YOLOv5 for training and detecting field marks. The project incorporates 3D localization to obtain a 2D plane representation of field and player detection.

The main file for the code is Final_Code.ipynb. Running it may require installing packages. The code can be executed by running each block down the line. Some blocks may be commented out as they are older versions of methods.

The output will be a video saved in the 'out' folder, which will be created during the execution of the code. The video showcases each of the methods (except field number detection) in one video.
