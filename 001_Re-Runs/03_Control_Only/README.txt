 - When the Branch tests are commented out, and test program is generated, QuestaSIM is unable to generate the dumpfile, that is why the Branch test is included in the TestProgramGenerator file.

- Line 119 was commented out in the first versions of TestProgGen for control test, and generated tst.src. I uuncommented it and tried running a new experiment on MULT1, with the newly generated test program, which is just 2 lines more than tst_01.src. Result was the same.

- Line 119 can be uncommented or not. It does not affect the program.
