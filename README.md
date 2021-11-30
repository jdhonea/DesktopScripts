# DesktopScripts

A collection of simple Linux scripts to make my life easier.

### MountNewDrive:

**Description:**  
Lists available drives and their partitions, allowing user to easilly mount them in their desired location. Support Luks encrypted drives.

**Usage:**  
`bash /path/to/mnd`  
or just copy mnd to /usr/bin and invoke normally.

### BatStat:  

**Description:**  
A simple script to poll all batteries in a system and quickly calculate remaining battery life based on current load on the system.

Created primarily for use with your favorite status bar. I ran into issues with battery plugins only showing battery life estimates per battery, instead of total.

![Batstat Screenshot](resources/ksnip_20211130-113301.png)  

**Usage**  
`bash /path/to/batstat`