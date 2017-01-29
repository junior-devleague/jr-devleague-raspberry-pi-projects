# Configuring the Raspberry Pi 2

## Setting up the Internet

### Ethernet (Mac)
This portion is configuring your Raspberry Pi to share a Macs internet connect if the Mac is connected through Wifi.

- Resource: https://galem.wordpress.com/2014/10/14/configuring-the-raspberry-pi-to-share-a-macs-internet-connection/

### Wifi
This portion is configuring your Raspberry Pi to connect to Wifi using Edimax, a wireless nano adapter.

- Resource: https://www.raspberrypi.org/forums/viewtopic.php?f=91&t=82908

## Controlling Raspberry Pi with SSH
This portion allows you access to the command line of a Raspberry Pi remotely from another computer or device on the same network using SSH.

- Finding the IP address of your Raspberry Pi
https://learn.adafruit.com/adafruits-raspberry-pi-lesson-3-network-setup/finding-your-pis-ip-address

- If your connection was refused
http://workshop.raspberrypiaustralia.com/ssh/network/2014/08/31/05-connecting-via-ssh/

Remotely connect to the Raspberry Pi with the command `ssh pi@[ipAddress]` and type in the password at the prompt.

- Resource: https://www.raspberrypi.org/documentation/remote-access/ssh/unix.md

## Installing Node.js and NPM to Run Live-Server

You know you are complete with you portion once you are able to run `live-server` on a JavaScript file.

- Resource: http://stackoverflow.com/questions/26320901/cannot-install-nodejs-usr-bin-env-node-no-such-file-or-directory
- Resource: http://weworkweplay.com/play/raspberry-pi-nodejs/
- Resource: http://askubuntu.com/questions/49390/how-do-i-install-the-latest-version-of-node-js

## Issues
- Raspberry Pi keeps on rebooting!!
  The voltage is low. Connect the power cord to an outlet.

