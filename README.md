# Serial_Multiplier_Volume_Control

This is a serial multiplier block for signals whose sampling frequency is at least 256 times lesser than the system clock.
This multiplier does not use FPGA DSP blocks, thus it helps to save DSP blocks by using these serialmultipliers for slow signals, 

while saving the DSP blocks for the high speed computations on high speed signal processing blocks.
The testbench for this block is in Myhdl and requires GHDL (for VHDL). 
