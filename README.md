# Deep Learning Techniques Applied to Estimate Music Gestural Patterns
The following code provide all the Deep Learning techniques applied in the paper using Keras framework. 

We used: 
- Python '3.6.8' 
- TensorFlow '2.0.0' 
- NumPy '1.17.4' 
- Scikit-learn '0.23.1' 
- Pyquaternion '0.9.5'.

## Music Score
8 Gestures were recorded by professional violinist and students in the Royal College of Music in London
![alt text](https://github.com/Dazzid/Deep_Learning_Techniques_Applied_to_Estimate_Music_Gestural_Patterns/blob/master/figures/01_music_score_eight_gestures.jpg)

## Gestures Shapes
All data normalised and centralised. The getures shapes are given by the Euler angles extracted from the IMU's Myo armband sensor. It outputs a Quaternion orientatoon data that was re-oriented and translated to Euler angles. 
![alt text](https://github.com/Dazzid/Deep_Learning_Techniques_Applied_to_Estimate_Music_Gestural_Patterns/blob/master/figures/12_Gestures.jpg)

## 3D Data Format
The shapeof the data to be passed to the LSTM models 
![alt text](https://github.com/Dazzid/Deep_Learning_Techniques_Applied_to_Estimate_Music_Gestural_Patterns/blob/master/figures/04_3D_Data.jpg)

## Deep Learning Models
![alt text](https://github.com/Dazzid/Deep_Learning_Techniques_Applied_to_Estimate_Music_Gestural_Patterns/blob/master/figures/06_CNN_Models.jpg)
![alt text](https://github.com/Dazzid/Deep_Learning_Techniques_Applied_to_Estimate_Music_Gestural_Patterns/blob/master/figures/07_LSTM_Models.jpg)
