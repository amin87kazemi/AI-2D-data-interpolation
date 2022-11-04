The file is a MATLAB matrix file. Case study 1 is for the PIV data interpolation, and case study 2 is for the CFD data interpolation.
When each is loaded in MATLAB, it shows 4 matrices:

Utrain: Includes the u component of the velocity for train data
Utest: Includes the u component of the velocity for test data (the area of artificial gap)
Vtrain: Includes the v component of the velocity for train data
Vtest: Includes the v component of the velocity for test data (the area of artificial gap)

In the above matrixes, 
column 1 is the x cordinate
Column 2 is the y cordinate
Column 3 is the velocity component on the right side of the point of interest,
Columns 1-3 are the inputs.
Column 4 is the output (either u or v)