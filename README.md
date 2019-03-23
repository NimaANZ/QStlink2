**QSTLink2**
========
[![GitHub version](https://badge.fury.io/gh/fpoussin%2Fqstlink2.svg)](https://badge.fury.io/gh/fpoussin%2Fqstlink2)  
[![Travis Build Status](https://travis-ci.org/fpoussin/QStlink2.svg?branch=master)](https://travis-ci.org/fpoussin/QStlink2) Travis - Ubuntu 16.04 - Qt5.5.1  
[![Build Status](https://jenkins.netyxia.net/buildStatus/icon?job=QStlink2%2Fmaster)](https://jenkins.netyxia.net/job/QStlink2/job/master/)  Jenkins - Ubuntu 18.04 - Qt5.9.5  


##Description  

QSTLink2 is a cross-platform STLinkV2 GUI.

It can perform the following actions:  

- Write
- Read
- Verify
- Erase

##Downloads  

Windows binaries:  
 - https://github.com/fpoussin/QStlink2/releases  

Ubuntu PPA:  
 - https://launchpad.net/~fpoussin/+archive/ppa  

##Building on Linux  

###Build dependencies:  
- qmake (Qt 5.2+)
- qtbase5-dev
- libqt5gui5-dev
- libqt5xml5-dev
- libusb-1.0
- libqt5usb5-dev (QtUSB https://github.com/fpoussin/QtUsb)

###Build steps:  
```
qmake
make
sudo make install  # Optional
```

##Building in Windows  

You will need to run these commands from MSVC's CLI (I use MSVC2017 community)  
You can also build from Qt Creator, which is a lot easier.

I recommend that you build/download a static version of Qt 5 for Windows.  
You can see how to do it here: https://github.com/fpoussin/Qt5-MSVC-Static

###Dependencies:  
 - MSVC 2013 or newer (community edition works fine)
 - QtUSB (https://github.com/fpoussin/QtUsb)
 - Qt 5.2 SDK or newer

###Build steps:  
```
qmake
nmake
```
