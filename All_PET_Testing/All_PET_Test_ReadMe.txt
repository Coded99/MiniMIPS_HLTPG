Step 1:
Edited the pseudo_template.py so that it will only generate PET test program for the MULT function.
The file is now named - All_PET_Test_Template.py

Step 2:
Created all.txt which contains all PET test patterns for add, logic, shift and sub. The patterns were copied from pseudo-exhaustive-data.txt, and 
was combined to be one file.

Step 3:
The patterns in all.txt was pasted into data.txt as per normal process.

Step 4:
The TestProgramGenerator.py was also edited not to generate Pipeline + co_processor test program as they are not needed.
In this case, the method generating PET test program is now being used to generate test program for only Mult PET as the pseudo_template.py 
file was edited.

Step 5:
FC simulation continued as per process for ADD, MULT0, MULT1 and PPS_EX circuits.

