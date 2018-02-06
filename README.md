# MemoryMonitor
You are doing some calculations on a big matrix, it's going to take some time so you execute your algorithm and leave for a cofee break, only to find when you return that your computer it's totally stuck and unresponsive because that big ass matrix exceeded your RAM capacity by so far that half of your memory has been dumped to swap. This calls for a Stanlinist approach to control everything the kernel loads, keeps and feels.

This package lets you monitor every symbol defined in multiple contexts and provides a memory watchdog to kill the kernel in case it grows out of your control and needs to be sent to the Gulag.

![monitor](https://github.com/CarlosManuelRodr/MemoryMonitor/raw/master/img/monitor.png)

![options](https://github.com/CarlosManuelRodr/MemoryMonitor/raw/master/img/options.png)

# Install

* If you are using v11.2 go to Palettes -> Install Palettes and select the appropriate file for your platform.

* If not, run the "MemoryMonitor_code.nb" file and install the palette by yourself.

# Requisites
Works best in Mathematica v11.2. It will run in previous verions (I have tested it in v11.1) but the measurement of free memory left is not accurate.