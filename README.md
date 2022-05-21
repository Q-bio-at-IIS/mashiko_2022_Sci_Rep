# Mashiko_2022_Sci_Rep
Image analysis code used in Mashiko et al. 2022 Sci. Rep. 

## Contents
This repository include
+ readme: this file
+ sample_code.nb: Mathematica code to run the image processing algorithm used in the paper.
+ TIFF: TIFF version of the image used in the sample.
+ vdatmod.xlsx: Manucally corrected nuclei centroid position data.
+ Dump: A folder in which Mathematica Dump files created in the sample code are stored.

## Installation: 
copy this following files in the repository by keeping the subfolder structure:
+ sample_code.nb
+ vdatmod.xlsx
+ TIFF/
+ Dump/

## Execution:
Open Sample_code.nb and run it with SHIFT+RETURN. All the lines are automaticaly executed.
Be sure that the Dump/ folder is created. Error occurs if it does not exist.

## Note
Sample_code.nb was implemented on Mathematica ver11 and tested by Mathematica ver10, ver 11 on Mac Book Pro with Intel processor and ver12 on MBP with M1 processor.
The latest version of Mathematica, especially that for Mac M1 processor, contains bugs around 3D visualization functions.
If the code crushes in your environment, please try Mathematica of older version on an Intel Mac computer.
Because the code load a pretty lage size of time-lapse volumetric data as one 4D matrix, sufficient amount of memory is requred to run the code. 
At leaset 16GB, more than or equal to 32GB memory is recommended. 
