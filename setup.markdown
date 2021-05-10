---
layout: default
title: Setup & Install
permalink: /setup/
nav_order: 2
---

## Getting ready for the workshop

In our workshop, we will be using Python 3 and the Jupyter Notebook environment in order to work with our data. We highly encourage participants to install everything in advance of the session and download the sample files, if possible. If anyone gets stuck, don't hesitate to reach out to the workshop conveners, Andrew Battista, Katie Wissel, and Daniel Hickey.

### Table of Contents
- [Installation instructions](#installation-instructions)
- [Getting the data](#getting-the-data)
- [Troubleshooting](#troubleshooting)

### Installation instructions

1. **Download and Install Python with the Anaconda 3 distribution.**
  Although there are many ways to install and run Python, and still many more ways to install the Anaconda 3 distribution and accompanying libraries, we are going to recommend using the appropriate graphical installer from Anaconda.
    + __Mac__ [instructions](https://docs.anaconda.com/anaconda/install/mac-os/)  (*Note: When you get to step 6, select "install for me only" and install it in a location on your personal user account.*)
    + __Windows__ [instructions](https://docs.anaconda.com/anaconda/install/windows/) (*Note: Make sure to select "just for me" and select the box that registers your Anaconda as the default Python 3.x. You may find these [instructions and video tutorial](https://datacarpentry.org/python-ecology-lesson/setup.html) to be helpful.*)
    + __Linux__ [instructions](https://docs.anaconda.com/anaconda/install/linux/)


2. **Install the `pyjanitor` library**  
  Our workshop will be using several libraries that come standard with the Anaconda distribution, but one does not: [pyjanitor](https://pyjanitor.readthedocs.io/installation.html). In order to install it, we recommend using the `conda` command.
  + __On Mac or Linux:__ Open a bash prompt, e.g., `Terminal` and run the command
  ```
  conda install pyjanitor -c conda-forge
  ```
  + __On Windows:__ Your new Anacondas installation should have installed a program called `Anaconda Prompt`. Open it and run the command
  ```
  conda install pyjanitor -c conda-forge
  ```

### Getting the Data
__Download the contents of this private [Box folder](https://nyu.app.box.com/folder/135087745557).__ To do so, you will need a Box account [using the email address](https://account.box.com/login?redirect_url=/folder/135087745557) you used when registering for the workshop. If this is not tenable, please reach out and we will find a different way to give you the data.

### Troubleshooting

We have discovered that problems can occur when users have previously installed Anaconda 3 on their machine. If this is happening, the best thing to do is uninstall your Anaconda 3 and then re-install it, making sure you have followed the above directions.

The installation of Anaconda 3 is fairly straightforward, but the Pyjanitor library is not standard and must be installed on top of Anaconda. In our experience, installing cleanly for only a single user on your machine should do the trick.
