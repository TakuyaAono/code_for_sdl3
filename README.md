# Game Programming in C++ Code
This repository contains the source code for *Game Programming in C++* by Sanjay Madhav.

The source code for the chapters is released under the BSD 3-clause
license. See LICENSE for more details. Note that this license does not apply to
the code in the External directory. Each External project is licensed separately.

# Building the Code
~~Each chapter's code is tested and works on both Microsoft Windows and Apple macOS.~~
Chapter 01's code is tested and works on both Microsoft Windows.

To compile on Windows, install MSYS2.
(https://www.msys2.org/#installation/).

To install MSYS2 + LLVM-MinGW.
```
pacman -Syu
pacman -Syu
pacman -S mingw-w64-clang-x86_64-toolchain
pacman -S mingw-w64-x86_64-gdb
pacman -S mingw-w64-clang-x86_64-sdl3
```

Add it to the PATH setting in the environment settings.
(Please change it to suit your environment.)
```
C:\msys64\clang64\bin
```


---
** NON CHECKING **

Code for Chapter 7 and beyond uses the FMOD API for audio. This requires
a separate installation from (https://www.fmod.com/download). Download
and install version 1.09.x of the FMOD Studio API (newer versions are untested).
On Windows, install FMOD to the default directory. On Mac, copy the contents
of the FMOD package into External/FMOD.
