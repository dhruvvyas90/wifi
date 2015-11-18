wifi
----

Wifi provides a command line wrapper for iwlist and /etc/network/interfaces
that makes it easier to connect the WiFi networks from the command line.  The
wifi command is also implemented as a library that can be used from Python.

Quick guide for installing it on Rpi

**Downloading and installing**
::
    # git clone -b rpi-branch https://github.com/dhruvvyas90/wifi
    # cd wifi
    # sudo python setup.py install

**cleaning up**
::
    # cd ..
    # sudo rm -r ./wifi/

.. image:: https://travis-ci.org/rockymeza/wifi.png?branch=master
   :target: https://travis-ci.org/rockymeza/wifi

The documentation for wifi lives at https://wifi.readthedocs.org/en/latest/.


