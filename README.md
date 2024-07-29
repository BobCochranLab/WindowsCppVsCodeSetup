# WindowsCppVsCodeSetup
This repository contains the .vscode folder I use for building and debugging C++
programs for Windows 11 when using the TDM-GCC-64 C++ compiler.

The files contained in the folder are launch.json and tasks.json.

Installing the TDM-GCC-64 C/C++ compiler is straightforward.  Go to https://sourceforge.net/projects/tdm-gcc/ and click the Download button.  A file called tdm64-gcc-5.1.0-2 (as of July 2024 - the version number will likely change in the future) will be downloaded to your Downloads folder.  This file is an installer executable, and does almost everything for you.  You can un-check the "Check for updated files on the TDM-GCC server" if you want to install without the latest updates.  When prompted for the optional components you wish to have installed, you probably want to check 'gdb' since that is the debugger, and the debugger is referenced in the launch.json file appearing in this repository.  When I did the installation, this box was unchecked as the default, so of course I checked it before I started the installation.
