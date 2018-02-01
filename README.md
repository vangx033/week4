#!/bin/bash
#Xee Ho Vang
#Chapter 3 script

echo "Here is my script for chapter 3."

#List what are in the /dev directory
ls /dev

#Change directory to /dev and check where am I
cd /dev
pwd

#Testing Kernel to ignore the input and view files
echo Hi there > /dev/null
ls -l

#Showing the path for the device sda
udevadm info --query=all --name/dev/sda

#Monitoring all the devices
udevadm monitor

#Change directory back to home and display a closing statement
cd
echo "Good bye and have a nice day

