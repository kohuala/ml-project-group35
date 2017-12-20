# Automatic License Plate Recognition and Registration System

* NOTE: we will complete this page and upload the ppt tonight, please visit later. Thanks.

Machine Learning Project by Group35:
* Huihua Guan
* Yi (Roy) Luo

## Project Aim and Problem Fumulation

For our project, we will focus on implementing a sign-in system in a parking lot. We would like to make the parking easier by automatically detecting the license plates instead of distributing physical tickets when cars enter or exit the parking lot. Other features such as number of passengers, colour of the vehicle, etc. can be derived from an image sequence or a video sequence of the vehicles at the checkin gate set at license plate level and pointing perpendicular to the plate to minimize skew.
To implement this design, we first must build a dataset with the appropriate characters. For the English letters, we can use the Char74k dataset. This famous dataset contains an assortment of images of 0-9 and A-Z and can be conveniently found at the following link http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/.


## Technology Overview

* First Step: We used SVM to train the model
* Second Step: We used connected region method to extract and segment the LP
* Third Step: We used the trained model to recognize characters
* Fourth Step: We registered or delisted the estimated LP into a csv file

## Evaluation

To be continued

## Reference
* http://www.ee.surrey.ac.uk/CVSSP/demos/chars74k/
* https://matthewearl.github.io/2016/05/06/cnn-anpr/
* https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721
* https://github.com/andela-foladeji/License-Plate-Recognition-Nigerian-vehicles

