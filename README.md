# Line Processor

## Overview
The purpose of this project is to gain experience in **C programming** with arrays and outputting text to the terminal. Given lines from a file or input from a user, the program outputs:
- Lines that are over 20 characters.
- The total number of lines.
- The longest line.
- The shortest line.

The challenge is to take any text file or user input and output the information in the correct format specified.

## How to Run and Compile:
To compile and run the project enter the following commands in the terminal while in the project folder:

```bash
gcc -o prog lineinfo.c  
./prog
```
Note: ignore any compiler warnings that may appear.

## Running the program with the given text file

To test the project with the given text file, after running the program select to run it with a text file and then enter "test_text.txt"

Running the program with the test file will give output in this particular format:
\*Warning\* Line 2 is truncated.  
\*Warning\* Line 5 is truncated.  
Total number of lines: 5  
The longest is Line 2: "This line will be tr" (len=20)  
The shortest is Line 4: "shortest" (len=8)  

This was the original test to check that the program was running perfectly. 
