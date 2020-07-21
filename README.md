
[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
# Applying Deep Learning Techniques to Estimate Patterns of Musical Gesture
The following code provide all the Deep Learning techniques applied in the related paper using Tensorflow library. 

We used: 
- Python '3.6.8' 
- TensorFlow '2.0.0' 
- NumPy '1.17.4' 
- Scikit-learn '0.23.1' 
- Pyquaternion '0.9.5'.

## Music Score
8 Gestures were recorded by professional violinist and students in the Royal College of Music in London.

<img src="https://github.com/Dazzid/Applying_Deep_Learning_Techniques_to_Estimate_Patterns_of_Musical_Gesture/blob/master/figures/01_music_score_eight_gestures.jpg" width=80%/>

## Gestures Shapes
All the data were normalised and centralised. The gestures shapes are given by the Euler angles extracted from the IMU's Myo armband sensor. It outputs a Quaternion orientation data that was re-oriented and translated to Euler angles.  

<img src="https://github.com/Dazzid/Applying_Deep_Learning_Techniques_to_Estimate_Patterns_of_Musical_Gesture/blob/master/figures/12_Gestures.jpg" width=60%//>

## 3D Data Format
The shape of the 3D data to be passed to the LSTM models is given by (Samples, Time-steps, Features). As you might see in the data/Gestures/All folder, features are organised in independent files from 1 to 9 wich each of them are the axes per sensor device (Accelerometer, Gyroscope and Magnetometer).

<img src="https://github.com/Dazzid/Applying_Deep_Learning_Techniques_to_Estimate_Patterns_of_Musical_Gesture/blob/master/figures/04_3D_Data.jpg" width=60%//>

## Licence
The following code and samples are released under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 (CC BY-NC-SA 4.0) license (http://creativecommons.org/licenses/by-nc-sa/4.0/)
