# Downloading and installing Python

*Depending on operating system you use there are diffrent options for downloading python.*

Installing or updating Python on your computer is the first step to becoming a Python programmer. 
There are a multitude of installation methods: you can download official Python distributions from 
Python.org, install from a package manager, and even install specialized distributions for scientific 
computing, Internet of Things, and embedded systems.

This tutorial focuses on official distributions, as they’re generally the best option for 
getting started with learning to program in Python.

In this tutorial you’ll learn how to:
* Check which version of Python, if any, is installed on your machine
* Install or update Python on Windows, macOS, and Linux
* Use Python on mobile devices like phones or tablets
* Use Python on the Web with online interpreters

*No matter what operating system you’re on, this tutorial has you covered. Find your operating system below and dive in!*

########################################################################################################

## How to Install Python on Windows

There are three installation methods on Windows:
* The Microsoft Store
* The full installer
* Windows Subsystem for Linux


-----------------------------------------------------------------
How to Check Your Python Version on Windows                     |
                                                                |
To check if you already have Python on your Windows machine,    |
first open a command-line application, such as PowerShell.      |
 - press windows key (the one with windows logo on it)          |
 - type powershell                                              |
 - press enter                                                  |
With the command line open,                                     |
type in the following command and press Enter:                  |
 '''                                                            |
    python --version                                            |
 '''                                                            |
-----------------------------------------------------------------

### How to Install From the Full Installer

For professional developers who need a full-featured Python development environment, installing from the full installer is the right choice. It offers more customization and control over the installation than installing from the Microsoft Store.

You can install from the full installer in two steps.
Step 1: Download the Full Installer

Follow these steps to download the full installer:

    Open a browser window and navigate to the Python.org Downloads page for Windows.

    Under the “Python Releases for Windows” heading, click the link for the Latest Python 3 Release - Python 3.x.x. As of this writing, the latest version was Python 3.8.4.

    Scroll to the bottom and select either Windows x86-64 executable installer for 64-bit or Windows x86 executable installer for 32-bit.

If you aren’t sure whether to select the 32-bit or the 64-bit installer, then you can expand the box below to help you decide.

For Windows, you can choose either the 32-bit or the 64-bit installer. Here’s the difference between the two:

    If your system has a 32-bit processor, then you should choose the 32-bit installer. If you attempt to install the 64-bit version on a 32-bit processor, then you’ll get an error at the beginning and the install will fail.

    On a 64-bit system, either installer will work for most purposes. The 32-bit version will generally use less memory, but the 64-bit version performs better for applications with intensive computation.

If you’re unsure which version to pick, go with the 64-bit version.

If you have a 64-bit system and would like to switch from 64-bit Python to 32-bit (or vice versa), then you can just uninstall Python and then reinstall it by downloading the other installer from Python.org.

When the installer is finished downloading, move on to the next step.
### Step 2: Run the Installer

Once you’ve chosen and downloaded an installer, run it by double-clicking on the downloaded file. A dialog box like the one below will appear:
Windows installation dialog

There are four things to notice about this dialog box:

    The default install path is in the AppData/ directory of the current Windows user.

    The Customize installation button can be used to customize the installation location and which additional features get installed, including pip and IDLE.

    The Install launcher for all users (recommended) checkbox is checked default. This means every user on the machine will have access to the py.exe launcher. You can uncheck this box to restrict Python to the current Windows user.

    The Add Python 3.8 to PATH checkbox is unchecked by default. There are several reasons that you might not want Python on PATH, so make sure you understand the implications before you check this box.

The full installer gives you total control over the installation process.
