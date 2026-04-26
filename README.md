# Assignment 1 - Circular Buffer in C

## Description

This project is about implementing a circular buffer in C. The buffer stores characters and allows writing and reading data using a circular approach instead of a linear one.

## What the program does

* Takes the user’s name as input
* Adds "ESY-CE" to the name
* Stores each character in a circular buffer
* Reads the characters back from the buffer
* Prints the final result
* Ensures the buffer is empty after reading

## Functions implemented

* Initialize the buffer
* Check if the buffer is full
* Check if the buffer is empty
* Write data into the buffer
* Read data from the buffer

## Notes

* The program handles buffer overflow (when the buffer is full)
* The program handles buffer underflow (when the buffer is empty)
* Circular indexing is done using the modulo operator (%)

## How to run

1. Compile the program:

```
gcc main.c -o main
```

2. Run the program:

```
./main
```

## Author

Aryam almurai
