# MPU6050-Accelerometer-Sample-Code
This is a sample python file to read the values of the MPU6050.
Make sure to install both i2c-tools and smbus modules prior to running
Also import os as we are using some os.system('clear') calls to keep the terminal screen clean between readings.
I like the fact that this uniot also provides temperature as I would like to mount this on an engine for detecting vibrations and it will be interesting to see the possible temperature and vibration correlations when readings deviate from nominal. 
