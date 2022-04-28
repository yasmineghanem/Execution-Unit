# Execution-Unit
A microprocessor execution unit using Quartus 

Input Command —> 10 bits
First two bits :  ALU selection
00 : MOV
10 : ADD
11 : AND

Second two bits : Destination register
00 : A
01 : B
10 : C

Third two bits : Source
00 : A
01 : B
10 : C
11 : Value

Last four bits : 
	—> Value if source is 11



Instructions in waveform:
Instructions	Input Command
MOV A , 6	   0000110110
MOV B , 2	   0001110010
ADD A , B	   1000010000
MOV C , A	   0010000000
AND B , A	   1101000000
ADD C , 4	   1010110100
AND C , 8	   1110111000







