# Key-signature-mapper
This program is designed to take an input audio and map it's contents to any specified key signature. The provided audio file is the one I used, but it can be changed to any desired audio file (under 30 seconds is recommended for run time purposes) as long as the file path name is changed when calling the function.

Using an FFT, the frequency contents of the input signal are analyzed. They are then shifted to the nearest frequency in a user specified key signature, and then converted to an output audio file using an inverse FFT. 

As this was created as a final project for a DST class, each cell in the program seeks to explain a part of the process and build the understanding and complexity as it goes on. Were I to continue developing it, I would use an STFT to impliment this. 
