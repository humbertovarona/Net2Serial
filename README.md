# Network client to forward data to RS232 serial ports (Net2Serial)

Version 2.0

#DOI

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.7374331.svg)](https://doi.org/10.5281/zenodo.7374331)

# Description

Net2Serial es utilizado para reenviar todos los datos de textos para varios puertos seriales que son recibidos desde un servidor con un puerto TCP especifico.

Created for coastal and oceanic navigation, being able to use the GPS data forwarded through a LAN network in several software simultaneously, it can also be used with other RS232 input devices (radars, echo-bathymeter, CTD, etc.) and with development boards (Arduino, ESP8266 and other devices that send information through RS232 ports).

This application is used in conjunction with applications that create virtual RS232 ports such as:

- Virtual Serial Port Driver
- com0com
- Free Virtual Serial Ports
- Virtual Serial Port Emulator
- Virtual Serial Port Kit

# How to install

Download it and copy it into a directory

## How to run

Just run it on windows and configure as a network client with the IP address of the server and the TCP port

## Operation mode

Run One4All on the computer where the devices with the sensors are, configure One4All as a network server with the local IP address and a specific TCP port. Install Net2Serial on the computers you want to run the device operation software and configure it as a network client with the IP address of the server and the same TCP port.

Run the "Virtual Serial Port Driver" on each network client and configure it with the number of serial port pairs needed, finally configure in Net2Serial each one of the serial ports that will be used as input and activate forwarding through from the LAN.
