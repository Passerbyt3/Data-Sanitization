---
layout: default
title: Page Name
---
## About
This document serves as documentation for the troubleshooting steps I did in order to get Eric Zimmerman’s Master File Table Explorer (MFTE) working on my machine (HP ProBook 450 G6) after I got the ‘This app can't run on your PC’ error. These steps may not work on all machines, however, they may still provide users with a general idea on what to do in case they run into similar errors.

I am not an expert on the subject and I am not associated with Eric Zimmerman in any capacity. I am just someone who uses his tools.

Download MFTECmd.exe from Eric Zimmerman’s Github page.

An official guide for Eric Zimmerman’s tools can be found at leanpub.

This document assumes you followed the requirements as stated on Zimmerman’s requirements & troubleshooting section.

PDF version with images available at [Visual Guide](https://passerbyt3.github.io/Data-Sanitization/Eric%20Zimmerman%20MFTECmd.pdf)

## Check for File Corruption
Check if your install is corrupt. This can be done by navigating to the directory the program is in and seeing whether the file size is 0 KB or not. If the file is not corrupt, then go to the file directory and launch the program from there.
## Go to File Directory
Before adding the program to your system environment variables, first go to the directory where the program is. Do this using cd /thepath/to/thefile. In my case, my path is  C:\Users\users\Desktop\, so I would do cd C:\Users\users\Desktop\ inside of an Administator terminal as the program can not run without administrator privileges.
## Adding MFTECmd.exe to the System Variables
After downloading the program, add it to your system variables. To do this, in the Windows search bar search for ‘environment’. Click on ‘Edit the system environment variables for your account’. Click on Path and then click ‘Edit…’. For the value of the path put the path where MFTECmd.exe is installed. After this step add the program(MFTECmd.exe) after the backslash. 
To test whether this worked, go to an administrator terminal on your machine and go to the directory where your file is and then run MFTECmd.exe in the command line.


