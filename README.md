# InsertionSortAssembly
Created an assembly program for insertion sort based on the insertion sort java code.

All code developed and tested on an ubuntu linux system.

This project helped understanding the basics of assembly code, how instructions work and how code writtenv in higher level languages are translated to lower level languages. It also helped in understanding the linux command line, memory, how to access array locations, etc. This project has different sections each well documented and have good documentation as well.

The Fill(addr, length) will create an array at address addr of length elements containing length unique integers in reverse sorted order. The main currently creates an array in memory of 6 integers : 9 1 3 5 1 2. After running the program and accessing the memory on a linux system preferably, the numbers are sorted in ascending order: 1 1 2 3 5 9.

To run the program:

Have the legv8emul and the program file in the same directory for ease.
Run: ./legv8emul insertionsort.legv8asm
Check the results by accessing the linux memory on the terminal. 

To check individual programs within insertionsort, such as fill, just run ./legv8emul fill.legv8asm.
