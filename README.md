# Process-Injection on Windows with C++

This repository contains a C program that demonstrates a basic example of process injection on a Windows system.

## Overview

The program uses the Windows API to inject a payload into a running process. The payload and the target process are hardcoded into the program for demonstration purposes.

The payload is generated using `msfvenom`, intended to display a message box with the text "Hello hackers".

The target process is `notepad.exe`, but this can be modified to any process that the user has permissions to manipulate.


