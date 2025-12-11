A program in C that will prompt the user to modify the volume of an audio file using command-line argument.

The program should accept three command-line arguments. 
The first is input, which represents the name of the original audio file. 
The second is output, which represents the name of the new audio file that should be generated. 
The third is factor, which is the amount by which the volume of the original audio file should be scaled.
For example, if factor is 2.0, the program should double the volume of the audio file in input and save the newly generated audio file in output.
The program should first read the header from the input file and write the header to the output file.
The r program should then read the rest of the data from the WAV file, one 16-bit (2-byte) sample at a time. 
The program should multiply each sample by the factor and write the new sample to the output file.
