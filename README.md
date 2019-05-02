README
================
Marc A.T. Teunis
5/2/2019

## ProM installation

This tutorial explains how to install ProM (current version 6.8) on a
Linux UBUNTU 18.04 Virtual Machine

## VM access

Login into your VM using the IP address and credentials obtained You can
do this using a Terminal (in RStudio, PuTTy, Win-SCP or Git Bash)

## Create new directory

Create a new directory for installation files ProM

``` bash
mkdir "proM"
cd proM
```

## Download ProM 6.8

We use curl to download the 6.8 version tar
archive.

``` bash
curl -O http://www.promtools.org/prom6/downloads/prom-6.8-all-platforms.tar.gz
```

## Unzip the archive (tar)

``` bash
tar -zxvf prom-6.8-all-platforms.tar.gz
```

## Once downloaded and unzipped you can run the program directly executing the following bash command

``` bash
./ProMPM86.sh
```

## Installing ProM packages

From <http://www.promtools.org/doku.php?id=prom68>

The downloads as mentioned above only contain the ProM 6.8 framework.
They do not contain the ProM 6.8 packages that contain the vast majority
of the plug-ins. Once the ProM 6.8 framework has been download (and
installed), the packages can be installed through the ProM 6.8 Package
Manager.

    Start ProM 6.8 Package Manager.
    
    You can do this by starting a shell or terminal, going to the folder where you have unpacked the archive, and by running the ProMPM68.sh file. On Mac OS X, please do not double click the ProMPM68.sh file, as this starts Xcode to edit the file instead of running it.
    
    Make sure the Not installed tab is shown and that the RunnerUpPackages package is selected. This should be done by default, but better to check anyways.
    
    Select the Install button. As a result, a lot of packages will be downloaded and installed. At the end, either wait for the External Packages Required dialog to close by itself, or select the OK button.
    
    Optional: Select the amount of memory ProM 6.8 may use in the bar at the bottom.
    
    Stop ProM 6.8 Package Manager.
