# Circular Buffer Implementation (Assignment 1)

## 📌 Overview

This project implements a **Circular Buffer (Ring Buffer)** in C as part of the CE-ESY course requirements. The implementation demonstrates efficient memory usage by reusing buffer space through circular indexing.

---

## ⚙️ Features

* Initialization of the circular buffer
* Writing data into the buffer (enqueue)
* Reading data from the buffer (dequeue)
* Handling edge cases:

  * Buffer Overflow (when full)
  * Buffer Underflow (when empty)
* Circular indexing using modulo operation

---

## 🧠 Concepts Covered

* Data Structures (Circular Buffer)
* Arrays and Memory Management in C
* FIFO (First In First Out) behavior
* Pointer manipulation
* Edge case handling

---

## 🚀 How It Works

1. The user enters their name.
2. The string `"ESY-CE"` is appended to the input.
3. Each character is stored in the circular buffer.
4. Characters are then read back from the buffer and printed.
5. The program ensures the buffer is empty after reading.

---

## 🧪 Testing

The program was tested with:

* Buffer size smaller than input → to verify **Overflow handling**
* Buffer size larger than input → to verify **normal operation**

---

## 🛠️ Technologies Used

* C Programming Language
* Standard Libraries:

  * `stdio.h`
  * `string.h`

---

## 📂 Project Structure

```
Assignment1/
│── main.c
│── README.md
```

---

## 👤 Author

**Aryam**

---

## ✅ Notes

* The buffer is implemented manually without using built-in data structures.
* Emphasis is placed on clarity, correctness, and proper handling of boundary conditions.

---
