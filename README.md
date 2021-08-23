# zlib1211
A "turn-key" zlib 1.2.11 project for Windows and Microsoft Visual Studio 2019

The code is untouched from the archive found on https://www.zlib.net/

The Visual Studio 2019 solution is in the VS2019 folder. I chose to create a new folder rather than upgrade the older VS projects.
The project is set up to build debug and release static and dynamic libraries for win32 and x64 bit targets. The project settings suppress Microsoft's 4996 warnings about using unsafe C library functions.
