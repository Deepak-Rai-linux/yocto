# yocto introduction guide

#################################################
#Author : Deepak Rai                            #
#Copyright (c)                                  #
#Contact : deepak.rai.linux@gmail.com           #
#################################################

This file will help you to get started with yocto

Foramlly "yocto" is the smallest number i.e. 10^(-24).

Yocto Project: The Yocto project is defined as "an open source collaboration project that provides templates, tools, and methods to help you create custom Linux-based systems for embedded products regardless of the hardware architecture."

Make sure your Build Host meets the following requirements:
    1. 50 Gbytes of free disk space
    2. Supported Linux distributions(Ubuntu 18.04 (LTS), Ubuntu 20.04 (LTS), Ubuntu 22.04 (LTS), Fedora 34, Fedora 35, AlmaLinux 8.5, Debian GNU/Linux 10.x (Buster), Debian GNU/Linux 11.x (Bullseye), OpenSUSE Leap 15.3)
    3.  Following tools and their respective versions:
        Git 1.8.3.1 or greater
        tar 1.28 or greater
        Python 3.6.0 or greater
        gcc 7.5 or greater
        GNU make 4.0 or greater

# In this exercise I will use Ubunto 20.04 (LTS) Distro

You must install following essential host-packages on the BUILD HOST.

"gawk wget git diffstat unzip texinfo gcc build-essential chrpath socat cpio python3 python3-pip python3-pexpect xz-utils debianutils iputils-ping python3-git python3-jinja2 libegl1-mesa libsdl1.2-dev pylint3 xterm python3-subunit mesa-common-dev zstd liblz4-tool"

use command: 
# sudo apt install gawk wget git diffstat unzip texinfo gcc build-essential chrpath socat cpio python3 python3-pip python3-pexpect xz-utils debianutils iputils-ping python3-git python3-jinja2 libegl1-mesa libsdl1.2-dev pylint3 xterm python3-subunit mesa-common-dev zstd liblz4-tool

