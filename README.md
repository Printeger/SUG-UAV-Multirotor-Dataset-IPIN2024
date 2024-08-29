# SUG-UAV-Multirotor-Dataset-IPIN2024

## Introduction
 This UAV dataset is presented to support UAV research, such as high-precision positioning and dynamic calibration. The dataset is divided into two categories, each part designed for different research needs. The first category of the dataset contained visual, inertial, and motor encoder information collected in the indoor motion capture room. This dataset provides accurate ground truth generated by motion capture, which is suitable for the study of the UAV dynamics model. Another category of data is collected in a variety of complex outdoor scenarios, and the multi-sensor fusion localization algorithm is used to generate high-precision ground truth trajectory, which could be used for research in UAV positioning and scene reconstruction in complex environments. A total of 9 sequences of the dataset were provided. In particular, the timestamps of raw measurements in each sequence have been well synchronized and accurately calibrated. 
 
 [Dataset Link](https://zenodo.org/records/13420960)

## UAV Setup
<p align = "center">    
<img  src="https://github.com/Printeger/SUG-UAV-Multirotor-Dataset-IPIN2024/blob/main/img/set1.png" width="400" /><img  src="https://github.com/Printeger/SUG-UAV-Multirotor-Dataset-IPIN2024/blob/main/img/set2.png" width="400" />
</p>



## Dataset Category Preview

| Category | Sequence number | Sensors | Trajectory shape | Length / Duration | Ground Truth |
|----------|-----------------|---------|------------------|-------------------|--------------|
| Dynamic Sequences | Seq 1 | Camera / IMU / Motor encoder | Circle | 30.432m / 27.050s | Motion capture |
| Dynamic Sequences | Seq 2 | Camera / IMU / Motor encoder | Vertical Oval | 18.568m / 43.351s | Motion capture |
| Dynamic Sequences | Seq 3 | Camera / IMU / Motor encoder | Saddle | 60.606m / 59.366s | Motion capture |
| Dynamic Sequences | Seq 4 | Camera / IMU / Motor encoder | Infinite | 57.479m / 110.784s | Motion capture |
| Dynamic Sequences | Seq 5 | Camera / IMU / Motor encoder | Square | 45.070m / 62.000s | Motion capture |
| Dynamic Sequences | Seq 6 | Camera / IMU / Motor encoder | Free | 71.004m / 241.960s | Motion capture |
| LiDAR Sequences | Seq 7 | LiDAR / IMU / UWB/GNSS | Circle | 139.424m / 136.903s | LIO |
| LiDAR Sequences | Seq 8 | LiDAR / IMU / UWB / GNSS | Free | 340.570m / 452.999s | GLIO |
| LiDAR Sequences | Seq 9 | LiDATR / IMU | Square | 76.317m / 341.300s | LIO |





