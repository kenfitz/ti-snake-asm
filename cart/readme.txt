# ti-snake-asm: This folder contains a cartridge version of ti-snake. 

The snakeC.a99 file can be built into a cartridge bin file that can be loaded with the Classic99 TI-99/4a emulator.
Use the Asm994a Assembler to build it with the following settings:
1. Under Assembler Options
   a. Check Def Regs (R0 - R15)
   b. Check Produce Listing File. This is very helpful in debugging with the Classic99 debugger.
   c. Check Produce HEX Obj File
   d. Check Produce Cart BIN File.
2. Specify the path for the LST file.
3. Specify the path for the HEX Object file.
4. Specify the path for the Cartridge BIN file.
5. Click "Run Assembler"

If the build folder is included in the repo, simply load the snakeC.apf file into the Asm994a Assembler. Everything should already be set up.

