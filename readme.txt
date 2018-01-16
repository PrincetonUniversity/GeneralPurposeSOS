Programming language: LabVIEW 2015 (http://www.ni.com/labview)

External library functions required for running the program:
1. Andor Software Development Kit (SDK) 2016 
(http://www.andor.com/scientific-software/software-development-kit)
2. LibTiff (used to handle TIFF files, http://www.libtiff.org/)
3. Thorlabs Motion Control Software (https://www.thorlabs.com/software_pages/ViewSoftwarePage.cfm?Code=Motion_Control&viewtab=1)

When you install the Andor SDK on a computer with LabVIEW installed, the SDK DLL and LabVIEW files will automatically copied into the LabVIEW installation directory. 

For LibTiff and Thorlabs functions to be used, one need to manually place the DLL and LabVIEW files into the LabVIEW installation directory. LabVIEW files need to be placed in the “user.lib” folder in the LabVIEW directory. 