# FreeRTOS---Queue-Matrix-Multiplication

## Customizing P_RM (Periodic Rate Monotonic Scheduler)

The file **P_RM.py** is a modified scheduler that uses **First Fit** instead of the current algorithm.

In windows the file in directory (C:\Program Files (x86)\SimSo\schedulers) can be replaced to accomodate the modified version of **P_RM.py**.

Result:

![GUI](https://github.com/adolfdcosta91/FreeRTOS---Queue-Matrix-Multiplication/blob/master/ScreenShot/ScreenShot2.png)

## Queue and Matrix Multiplication

Matrix multiplication task is scheduled and stored on a Queue and displayed on a (10 X 10) matrix. 

Code:

**main.c** file

Result:
![GUI](https://github.com/adolfdcosta91/FreeRTOS---Queue-Matrix-Multiplication/blob/master/ScreenShot/ScreenShot.png)
