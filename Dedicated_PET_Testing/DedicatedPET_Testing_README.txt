Step 1:

Removed all the data in data.txt.
The code in the pseudo_template.py is reverted back to the original, so that it can generate PET test program for add, sub...logic.txt.

Step 2:

Edited TestProgramGenerator.py, such that it only generates the the test program based on the dedicated(original) Pseudo-exhaustive data in add.txt, logic.txt, mult.txt, shift.txt and sub.txt. 
The new TestProgramGenerator for this function is named TestProgGen_DedicatedPET.py

Step 3:

Perform testing as usual, generating tst.src and so on. FC simulation continued as per process for ADD, MULT0, MULT1 and PPS_EX circuits.
