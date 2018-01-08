# Mikes_Nucleo32
Getting a STM32F303 up and running

Open a terminal in ubuntu: there is always a terminal program include but there are some other ones
that you can install: konsole or Terminator

sudo apt-get install python-pip python-dev build-essential git
sudo pip install --upgrade pip 
sudo pip install --upgrade virtualenv 


Download embedded Gcc compiler
https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads
gcc-arm-none-eabi-7-2017-q4-major-linux.tar.bz2
version might change.

cp the tar file to /opt
tar xjf gcc-arm-none-eabi-7-2017-q4-major-linux.tar.bz2
ls to list all of the directories in /opt
There should be a directory: gcc-arm-none-eabi-7-2017-q4-major
Rename this using the mv command
mv gcc-arm-none-eabi-7-2017-q4-major gcc-arm-none-eabi

Now there should be a dir:gcc-arm-none-eabi

In opt create a directory called repos
mkdir repos

Install mbed os commandline tool:
pip install mbed-cli







