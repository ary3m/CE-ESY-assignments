# Assignment 1 - Circular Buffer in C

## Description

This project implements a circular buffer using the C programming language. The buffer stores characters and uses a circular approach to reuse space efficiently instead of stopping at the end of the array.

## Program Behavior

* The program asks the user to enter a name
* It appends "ESY-CE" to the entered name
* Each character is stored in the circular buffer
* The data is then read back from the buffer and printed
* At the end, the program confirms that the buffer is empty

## Implementation Details

The buffer is implemented using a struct that contains:

* A fixed-size character array
* A write index (for inserting data)
* A read index (for retrieving data)
* A counter to track the number of elements

The following operations are implemented:

* Buffer initialization
* Check if the buffer is full
* Check if the buffer is empty
* Write operation (with overflow handling)
* Read operation (with underflow handling)

## Key Concept

Circular behavior is achieved using the modulo operator:
(index + 1) % BUFFER_CAPACITY

This allows the indices to wrap around to the beginning of the array.

## How to Run

1. Compile the program:

```
gcc main.c -o main
```

2. Run the program:

```
./main
```

## Notes

* The program handles overflow when the buffer is full
* The program handles underflow when the buffer is empty
* The implementation is done manually without using built-in data structures

## Author

Aryam almurai
