---
layout: post
title:  "Installation of Python on Windows 10 "
date:   08-02-2020
categories: python installation windows
---
### Installation of Python on Windows 10 

To use Robot Framework, we first need to install python.

Newer versions of Robot framework will only support python 3.6 and above (at time of writing 2.7 and 3.3 are supported, to be dropped in 2021), below we will download and install the latest version of Python 3

Before we install python we need to know what the architecture of our computers processor and our installed operating system is, this could be 32bit or 64bit and we will want to download the correct matching python installer. 

We can check what we type of operating system we have by pressing the windows key and typing ```control``` then from the results select control panel.

Choose to view by small or large icons and click on the system icon if this is your first visit to the control panel and click on the System Icon.

In this system window if we take a look at the system type we can see that we have a 64 bit system, so now we know what python installation type to obtain.

Installation of python on a windows machine is an easy download and install operation, open a browser and navigate to [www.python.org/downloads](https://www.python.org/downloads "www.python.org/downloads").

Scroll down to the looking for specific release section and click on the download link for the latest version, scroll down the this page until you see the files section.
In the files section choose windows x86 dash 64 executable installer, this will download the 64 bit python installer we require.

Once downloaded run the installer, on the installers first dialog, before clicking on install now, check the Add Python to Path Checkbox. This will add Python to the systems environment variables, this tells Windows where Python is installed and is required.
We can leave the install for all user’s checkbox checked and click install now.
After a short time we are shown, Setup was successful, we can now close the installer.

To test that our setup was indeed successful open the Windows start menu and type ```cmd```
Click on command prompt in the results.

In the open command prompt type ```python --version``` and press enter.
We are returned the installed python version number, this means our python installation was successful.
