This program requires user input as a python file name, 
an input text file name and bit length through command line.

compression:

The input data is encoded using the LZW_Compresse.py file,

the dictionary of size 256 is built and initialized,

using the python dictionary data structure

in the dictionary, key are characters and values are the ascii values

the lzw compression algorithm is applied and we get the compressed data,

the program outputs the compressed data and stores it to an 

output file named inputFileName.lzw

The compressed data is of 2 bytes.




How to run the file:

To encode, type: 
	
	python LZW_Compresse.py file.txt 64


