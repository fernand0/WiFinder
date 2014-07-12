WiFinder
========
By using nmap, this script scan the number of hosts connected to the network, to play an 'alarm' when the value changes.

The aim is to be warned ahead of time (depending on the signal strength), before unexpected arrival of any roommates.

MacFinder
========
It checks the connected devices in the local network and stores them in a file. 
It uses the MAC address of the devices.
It also allows to name the devices (like Fing for Android).
In my system (Ubuntu) you need to run the program with sudo:
sudo python macfinder.py 
It drops privileges when it does not need them anymore.

## Install

To run the script are required Python and Nmap, which can be found at the following : 

* https://www.python.org/downloads/

* http://nmap.org/download.html

Also, take a look here : https://pypi.python.org/pypi/python-nmap
