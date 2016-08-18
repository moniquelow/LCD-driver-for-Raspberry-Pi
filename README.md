# LCD-driver-for-Raspberry-Pi
Installing the RPi LCD touch screen driver for Raspberry Pi3

You can use the last Raspbian firmware, then install driver to use this LCD; 
## Make sure you have enable your Raspbian OS desktop.On the Terminal, enter
sudo raspi-config


Enable Boot to Desktop/Scratch -> Desktop Log in as user 'pi' at the graphical desktop 

If your Raspbian OS is the newest 2016-05-10-raspbian-jessie or newer than it, you must install the Driver File:LCD-show-160715.zip 
(http://www.raspberrypiwiki.com/index.php/File:LCD-show-160715.zip)

If your Raspbian OS is the old One or your OS is Ubuntu mate, you must install the Driver File:LCD-show-151102-V2.zip 
(http://www.raspberrypiwiki.com/index.php/File:LCD-show-151102-V2.zip)

## Copy LCD-show-151102.tar.gz to your Raspbian OS then unzip it. On the LXTerminal:
tar xvf LCD-show.tar.gz
cd LCD-show/

#for 2.4 or 3.2 inch RPi LCD
sudo ./LCD32-show

#for 3.5 inch RPi LCD
sudo ./LCD35-show

#for 4 inch RPi LCD
sudo ./LCD4-show

#for 5 inch RPi LCD
sudo ./LCD5-show

## Then the Raspberry Pi will reboot, After reboot, wait for a munite, the LCD can display and touch

