# connect-it
iot api for deployment on rasp

# Content
* [Summary](#summary)
* [Resources](#resources)
* [Hardware](#hardware)
* [Software](#software)
* [Libraries](#libraries)
* [Documentation](#documentation)

# Summary
It is planned to collect resources and develop an app in order to do the following things:
* set up a redirection by upnp from a rasp (compute module + wifi ?)
* connect and update a dyndns service OR prepare an own equivalent, using a unique device id.
* host a micro website on the device, allowing for a direct on site connection,
* write a rest API for communication from internet (using whatever -> mobile app, central website ...)
* control a webcam
* control simple GPIO devices
* automatised update deployment 

# Resources
## Hardware
* [Rasp compute module](https://www.raspberrypi.org/documentation/hardware/computemodule/README.md)

## Software
* [Mini upnp](http://miniupnp.free.fr/)
* [Motion](https://wiki.debian.org/fr/Motion)

## Libraries
* [Flask](http://flask.pocoo.org/)
* [Django](https://www.djangoproject.com/)

## Documentation
### Some useful links from the [Raspberry Documentation](https://www.raspberrypi.org/documentation/):
* [How to build a Kernel on rasp](https://www.raspberrypi.org/documentation/linux/kernel/building.md)
* [Installing OS on rasp](https://www.raspberrypi.org/documentation/installation/installing-images/README.md)
