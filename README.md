# APRX Pi
APRX Raspberry Pi Distribution. The goal is to make an easy to install/deploy APRX gateway in one package.  

## Supported TNC/Devices
Currently we only support the [TNCPi](https://tnc-x.com/TNCPi.htm) as that is the hardware I have access to.  Others can be supported as time/equipment allow

## Download
Downloads are available as releases from [releases](https://github.com/toddejohnson/aprxpi/releases)

## Installation
1. Download the file from [releases](https://github.com/toddejohnson/aprxpi/releases)
2. Unzip the image and install it to an sd card [like any other Raspberry Pi image](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)
3. Configure your WiFi by editing aprxpi-wpa-supplicant.txt or aprxpi-network.txt on the root(boot partition) of the flashed card when using it like a thumb drive
4. Configure RMS/PAT settings by editing aprxpi.txt on the root(boot partition) of the flashed card
5. Log into your Pi via SSH (it is located at aprxpi.local if your computer supports bonjour or the IP address assigned by your router), default username is "pi", default password is "raspberry", change the password using the passwd command

## Credit
This is based upon:
* APRX https://github.com/PhirePhly/aprx
* CustomPiOS/OctoPi distro builder https://github.com/guysoft/CustomPiOS

