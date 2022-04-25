
This is codes for generating parameters and control variables for MHz inverter systems with 
impedance compression network. To use this code, Matlab above 2018b is needed.


The functions of the five documents are as follows:
Step1_ Zn: generate load impedance point set;
Step2_ Xu: obtain the upper branch parameters XU1 and XU2;
Step3_ XL: Obtain the lower branch parameters XL1 and XL2;
Step4_ IUIL: obtain control variables ∠ IU ', ∠ IL';
Step5_ VUVL:obtain voltage VU and VL.


By pasting them into the editor of MATLAB and running them 
step by step, the parameters and control set can be generated.


The variables that need to be adjusted manually are:

Load range Zo:                 Zomin，Zomax，fomin，fomax；
Ideal impedance range:   Zmin, Zmax, Fmin, Fmax;
Scanning steps:                (the number of steps determines the calculation accuracy and speed)

The files are generated in the local D disk. Please make sure that each time the codes are re-runed, 
the files with the same name generated in the last run are cleared.

