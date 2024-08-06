# Process-Injection on Windows with C/C++

- This repository contains C/C++  programs that demonstrate examples of process injection techniques on a Windows system.

## Overview

- The program uses the Windows API to inject a payload into a running process. The payload and the target process are hardcoded into the program for demonstration purposes.

- The payload is generated using `msfvenom`, intended to display a message box with the text "Hello hackers".

- The target process is `notepad.exe`, but this can be modified to any process that the user has permissions to manipulate.

## [ClassicProcessInjection](https://github.com/trevorsaudi/Process-Injection-cpp/tree/main/ClassicProcessInjection)

- Standard classic process injection featuring common API calls like `VirtualAllocEx`, `WriteProcessMemory`, `CreateRemoteThread`.

## [QueueUserAPC](https://github.com/trevorsaudi/Process-Injection-cpp/tree/main/QueueUserAPC)

- QueueUserAPC is a more sophisticated process injection technique that leverages the Windows Asynchronous Procedure Call (APC) mechanism. It features the `QueueUserAPC()` windows API.
