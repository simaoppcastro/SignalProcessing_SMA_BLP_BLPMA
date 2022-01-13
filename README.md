# Simple Signal Processing Filters: SMA, BLP, etc.

## Requirements:
pandas
numpy 
matplotlib

## Project Description:

Demonstration of simple signal processing filters such as SMA (Simple Moving Average), BLP (Butterworth Low Pass) and BLPMA (Butterworth Low Pass Moving Average). The program was used in a real-world application to filter the signal from the Essential Reality P5 glove. In this case it is a signal from the X position.

 - The P5 virtual reality gloves are data gloves suitable for gaming and 3D virtual environments. 
 - The gloves contain two infrared sensors. They detect the visible LEDs on the glove (there are eight in total) and convert them to the position (x, y, z) and orientation in terms of pitch, yaw and roll. The glove also has bend sensors in the fingers and four buttons on the top. 
 - Communication between the gloves and the application on the computer is via USB port.


<p align="center">
  <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/GIF/ALL.gif" width="800" height="450">
</p>

## Project Hierarchy:

## Application:

**Raw Data:**
<p align="center">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/Images/RAW.png" width="800" height="450">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/GIF/RAW.gif" width="800" height="450">
</p>

**Simple Moving Average (SMA):**
<p align="center">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/Images/SMA.png" width="800" height="450">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/GIF/SMA.gif" width="800" height="450">
</p>

**Butterworth Low Pass (BLP):**
<p align="center">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/Images/BLP.png" width="800" height="450">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/GIF/BLP.gif" width="800" height="450">
</p>

**Butterworth Low Pass Moving Average (BLPMA):**
<p align="center">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/Images/BLPMA.png" width="800" height="450">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/GIF/BLPMA.gif" width="800" height="450">
</p>

**ALL:**
<p align="center">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/Images/ALL.png" width="800" height="450">
 <img src="https://github.com/rparak/Simple_Signal_Processing/blob/main/GIF/ALL.gif" width="800" height="450">
</p>

## License
[MIT](https://choosealicense.com/licenses/mit/)

