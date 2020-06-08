Sonic 2 Split Disassembly (By Kurk)
=
Notes on the state of this disassembly:
-

* There are multiple asm files present in the files for here. S2Rev01.asm is (for now) the main asm file used in assembly. In the "old attempts" folder there are 2 asm files from earlier attempts to disassemble this in IDA. There are also .idb files of these as well. "S2Rev01Improved.idb" is the source of the "S2Rev01.asm" used while assembling. the other 2 idb's in the folder are the earlier attempts, with one made using lab313ru's smd ida loader.

* The produced rom is not bit-perfect yet. This is due to whatIi believe to be the assembler incorrectly assembling the non-split data (ie: mappings, art, dplc, music, etc)

* Many peices of data are fused with adjacent code in the main asm file. This also may be causing issues with bit-perfection. I am working to split these.

* SonLVL projects do not work at the moment.

Credits:
-
* Kurk: Main disasm attempts
* Ralakimus: Advice on how to improve this disasm.
* Rivet: Bug Reporting
* Gerbilsoft: Program used to compare the S2Built with a normal S2 Revision 1 rom.
* Xenowhirl: Split.bat program from his disasm

See Readme.txt for information on files in the disasm.
-
