# Gesture-Controlled-Omnidirectional-Robot
#### This is the official repository for the omni directional hand gesture robot project at IvLabs, VNIT Nagpur.

# Objectives
##### The objectives of the summer internship were to create a omni directional robot which move in all 8 direction using transmitter receiver with hand gesture.

# Methodology
## Software Implementation:
### 1. Connection of MPU6050 with ESP32
#### Connected an MPU6050 to an ESP32 as the following connection. The MPU6050 is an inertial measurement unit(IMU) that is a combination of gyroscope and accelerometer in all 6 dimension, which can detect the orientation, motion, and acceleration of the hand and give its value of each change to ESP32.
<img src="https://hackmd.io/_uploads/SkmLKjrP0.png" width="450" height="450"/>

### 2. Simulation result of MPU6050
#### MPU6050 track each movement and send its value to ESP32 as shown in the result shown below.
<img src="https://github.com/user-attachments/assets/5237a5b0-dc07-4db9-a93a-7b81af47e2ab">

### 3. Motion of Omnidirectional robot

#### (i) Forward motion &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; (ii) Backward motion
<img src="https://github.com/user-attachments/assets/424e7642-6287-4aa8-9a41-1e6ad27efb7e" width="355" height="355"/>
<img src="https://github.com/user-attachments/assets/5f020d86-c73c-4ddc-a0dd-8eceffe74d2b" width="355" height="355"/>

#### (iii) Leftward motion &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;&nbsp; (iv) Rightward motion
<img src="https://github.com/user-attachments/assets/437b1498-d7fa-4db3-be33-aff256ef7fd0" width="355" height="355"/>
<img src="https://github.com/user-attachments/assets/a5861f71-0ac9-4479-8c05-ab8ac25f3630" width="355" height="355"/>

#### (v) Anti-Clockwise Rotation &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; (vi) Clockwise Rotation
<img src="https://hackmd.io/_uploads/HJr1hVH_C.gif" width="355" height="355"/> <img src="https://hackmd.io/_uploads/Bkhg2VB_A.gif" width="355" height="355"/>

#### (vii) Forward-left motion (viii) Forward-right motion (ix) Backward-left motion (x) Backward-right motion
<img src="https://hackmd.io/_uploads/rJsTrrHOA.gif =355x" width="355" height="355"/> <img src="https://hackmd.io/_uploads/HyqAHHBdC.gif" width="355" height="355"/>
<img src="https://hackmd.io/_uploads/HyEJISHdA.gif" width="355" height="355"/> <img src="https://hackmd.io/_uploads/SkKJUHHuR.gif" width="355" height="355"/>
