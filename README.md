# IClinfMRI

Please cite the following publication if you use this software:

Hsu AL, Hou P, Johnson JM, Wu CW, Noll KR, Prabhu SS, Ferguson SD, Kumar VA, Schomer DF, Hazle JD, Chen JH, Liu HL. IClinfMRI software for integrating functional MRI techniques in presurgical
mapping and clinical studies. Front Neuroinform. 2018 Mar 9;12:11. <https://doi.org/10.3389/fninf.2018.00011>

## Installation
#### **IClinfMRI** software requires

| Software      | Version | Link                                             |
| ------------- |:-------:| ------------------------------------------------:|
| MATLAB        | 2014a*  |  
| SPM12         | v6685   | http://www.fil.ion.ucl.ac.uk/spm/software/spm12/ |
| dcm2nii       |         | https://www.nitrc.org/projects/dcm2nii/          |
| AFNI          |         | https://afni.nimh.nih.gov/                       |

to be installed and their functionalities verified before using IClinfMRI.


*Since AFNI is designed to run on Unix or Mac OS, those using a Windows operating system must install a virtual machine to run IClinfMRI.*

**IClinfMRI was developed under the MATLAB 2014a. Its functionality may be limited when using other MATLAB versions.*

#### Steps:

1. After downloading this software, please unzip the IClinfMRI_v111.zip file to a local directory. 

2. Under the MATLAB environment, the user can click on “Set Path” and add the local directory containing IClinfMRI to the path to complete the installation


## Getting started

Please use terminal to launch the MATLAB for building up the link of afni and dcm2nii from the terminal to MATLAB.
In the terminal window, type:
```
matlab
```
to launch the MATLAB.

Then in the MATLAB command window, type:
```
IClinfMRI 
```
to opens the main GUI window. 

*Key arguments specified in the functions are described in the published paper (<https://doi.org/10.3389/fninf.2018.00011>).*
