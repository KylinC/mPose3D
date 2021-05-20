# mPose3D
> Millimeter-wave human pose estimation

<p align="left">
    <a href="https://github.com/KylinC/mmVital-Signs"><img src="https://img.shields.io/badge/Python-3.6-blue" alt="GitHub version"></a>
    <a href="https://github.com/KylinC/mmVital-Signs"><img src="https://img.shields.io/badge/C%2FC%2B%2B-98-yellow" alt="GitHub version"></a>
    <a href="https://github.com/KylinC/mmVital-Signs"><img src="https://img.shields.io/badge/TI%20mmWave%20SDK-3.5.x.x-orange" alt="GitHub version"></a>
    <a href="https://github.com/KylinC/mmVital-Signs"><img src="https://img.shields.io/badge/CCS-8.3.1-lightgrey" alt="GitHub version"></a>
  </p>

The [mPose3D](https://github.com/KylinC/mPose3D) aims at human pose resonstruction and provide standard python API from [Texas Instrument](https://www.ti.com.cn/) (TI) mmWave hardware, such as xWR14xx, xWR16xx and xWR68xx.

### Experiment Environment

> Detection range covers the rectangle area of **5m x 3m**.

![IMG_9354](http://kylinhub.oss-cn-shanghai.aliyuncs.com/2021-05-19-121039.jpg)



### Demo

> Ground Truth - Feature - Prediction

<img src="https://github.com/KylinC/mPose3D/blob/main/docs/cut2.gif" height="300" />

> Video - Kinect Ground Truth - Prediction

<img src="https://github.com/KylinC/mPose3D/blob/main/docs/cut.gif" height="300" />



### Requirements

| **Item**     | **Details**                                                  |
| ------------ | ------------------------------------------------------------ |
| Device       | [IWR1443BOOST](http://www.ti.com/tool/IWR6843ISK) **OR** [ADC1000EVM](http://www.ti.com/tool/IWR6843ISK-ODS) |
| Power Supply | 5V, 3A with 2.1-mm barrel jack (center positive). The power supply can be wall adapter style or a battery pack with a USB to barrel jack cable. |
| Python 3.6   | All package included in requirements.txt                     |