---
layout: page
title: Setup
permalink: /setup/
---

## Getting ready for the workshop

In our workshop, we will be using Python 3 and the Jupyter Notebook environment in order to work with our sample data. We highly encourage participants to install everything in advance of the session and download the sample files, if possible. If anyone gets stuck, don't hesitate to reach out to the workshop conveners, Andrew Battista, Katie Wissel, and Daniel Hickey.

### Download and Install Python with the Anaconda 3 distribution

Although there are many ways to install and run Python, and still many more ways to install the Anaconda 3 distribution and accompanying libraries, we are going to recommend using the appropriate [graphical installer from Anaconda](https://docs.anaconda.com/anaconda/install/).

Once you have downloaded the install package, follow the instructions. If you're installing on a Mac OS, [pay attention to the instructions and screenshots](https://docs.anaconda.com/anaconda/install/mac-os/). Specifically, when you get to step 6, select "install for me only" and install it in a location on your personal user account. Similarly, if you are [installing on Windows, select "just me"](https://docs.anaconda.com/anaconda/install/windows/). We recommend following the advice of not adding Anaconda to your PATH environment variable. However, **please do select the box that registers your Anaconda as the default Python 3.x.** You may find these [instructions and video tutorial](https://datacarpentry.org/python-ecology-lesson/setup.html) to be helpful.

### Install the pyjanitor library

Our workshop will be using several libraries that come standard with the Anaconda distribution, but one does not: [pyjanitor](https://pyjanitor.readthedocs.io/installation.html). In order to install it, we recommend using the conda command. Open up a bash prompt, either Terminal for Mac or Git Bash or Powershell for Windows and run:

```
conda install pyjanitor -c conda-forge
```
### Troubleshooting if Conda is not found

We have discovered that problems can occur when users have previously installed Anaconda 3 on their machine. If this is happening, the best thing to do is uninstall your Anaconda 3 and then re-install it, making sure you have followed the above directions.
