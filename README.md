# SelfPiBox
PhotoBooth for Party selfies with a Raspberry Pi and RPi Camera written in Python

## Installation
On a fresh new Raspberry Pi Os updated & upgraded no package installation is required. 

You have to activate Camera Interface running 

`sudo raspi-config`

Just clone the repo in the opt folder :

`cd /opt`

`sudo git clone https://github.com/R-Men/SelfPiBox.git`

Navigate into SelfPiBox folder freshly created and launch the script : 

`cd SelfPiBox`

`python SelfPiBox`

You can use the startup script to launch it at boot.

## Hardware 
A screen must be attached to the HDMI output

You will need a button on RPi Pin #26 and if wanted a LED on PIN #13

## Testing without screen attached
You can use `tightvncserver`as a virtual screen. Your screen must have a resolution of 1920x1080.

`tightvncserver -geometry 1920x1080`

### Default Event Image 
[Original Flickr image](https://flic.kr/p/LhSZBG) of [event.png](assets/background/event.png) that was resized in 4:3. 
