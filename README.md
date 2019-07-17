# VIPM to NIPM Converter - Utility
 
The utility will load all the VIP files and add the packages to the VIPM package repository
Then based on the labview versions configured, each package will be applied in each labview version and then each VIP will be converted into NIPKG for that labview version.
Make sure the source folder contains the VIP files and the right destination folder is selected.


Limitations :
1. If the VIP file has Post install (Uninstall) or Pre install (Uninstall), this utility will not work
2. If the VIP file has some dependencies (Can be noticed from the parallel spec file), this converter will not convert the dependencies.
