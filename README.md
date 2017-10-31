# Digital Race
## Source code from 2016-2017 finalists
1. [Học viện kỹ thuật quân sự](https://github.com/fpt-corp/DriverlessCarChallenge_MTARacer)
2. [Đại học Bách Khoa TP.HCM](https://github.com/fpt-corp/DriverlessCarChallenge_CDIO)
3. [Đại học Lạc Hồng](https://github.com/fpt-corp/DriverlessCarChallenge_LHURacing)
4. [Đại học FPT](https://github.com/fpt-corp/DriverlessCarChallenge_AlphaOne)
5. [Đại học Công nghệ - ĐHQG Hà Nội](https://github.com/fpt-corp/DriverlessCarChallenge_TechColor)
6. [Đại học Công nghệ thông tin - ĐHQG TP.HCM](https://github.com/fpt-corp/DriverlessCarChallenge_SeBoys)
7. [Học Viện Công nghệ Bưu chính Viễn thông](https://github.com/fpt-corp/DriverlessCarChallenge_PTIT)
8. [Đại học Bách Khoa Hà Nội](https://github.com/fpt-corp/DriverlessCarChallenge_BKAKid)


Software for the Driverless Car 2017.

# [ROS PACKAGE](https://github.com/fpt-corp/ROS_Package_DriverlessCar)

## [ROS Tutorials](https://github.com/fpt-corp/ROS-Tutorials)

[Digital Race](https://cuocduaso.fpt.com.vn/en) 

[FPT Digital Race Youtube Channel](https://www.youtube.com/watch?v=ReT8AF0dVFs)

## Setup Instructions

### Contents
1. [Install Prerequisites](#1-install-prerequisites)
2. [Clone repository](#2-clone-or-fork-repositories)

### 1. Install Prerequisites
1. __Install [Ubuntu 14.04](http://www.ubuntu.com)__
2. __Install required packages__

##install CMake:
$ sudo apt-get install software-properties-common
$ sudo add-apt-repository ppa:george-edison55/cmake-3.x
$ sudo apt-get update
$ sudo apt-get install cmake

**********************************
##install Astra Camera Driver and OpenNI2:
use OpenNI-Linux-Arm-2.3
run install.sh to generate OpenNIDevEnvironment, which contains OpenNI development environment 

$ sudo chmod a+x install.sh
$ sudo ./install.sh

please replug in the device for usb-register
add environment variables.

$ source OpenNIDevEnvironment


********************************************
##install I2C For JetsonTK1

$ sudo apt-get install -y i2c-tools
$ apt-cache policy i2c-tools

********************************************
##install GIT

$ sudo apt-get install git

********************************************
##install PWM Servo Driver Board 

$ sudo apt-get install libi2c-dev i2c-tools
$ sudo i2cdetect -y -r 1

#JHPWMDriver Install
Set time and date first
  
### 2. Clone or Fork Repositories



