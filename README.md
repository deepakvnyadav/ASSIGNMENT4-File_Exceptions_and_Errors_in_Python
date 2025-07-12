# Assignment 4: Files, Exceptions, and Errors in Python

This repository contains solutions to **Assignment 4** of the Python course, focusing on file handling, exception handling, and error management in Python.

---

## 📁 Module:
**Module 5: Files, Exceptions, and Errors in Python**

---

## ✅ Task 1: Read a File and Handle Errors

### 🧾 Problem Statement:
Write a Python program that:
1. Opens and reads a text file named `sample.txt`.
2. Prints its content line by line.
3. Handles errors gracefully if the file does not exist.

### 💻 File:
- `task1_read_file.py`

### 🧪 Sample Output:

If the file exists:
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

###### Task 2: Write and Append Data to a File

## 📘 Description

This Python script performs file operations including writing user input to a file, appending additional data, and finally reading and displaying the complete content of the file.

It is part of **Assignment 4** under **Module 5: Files, Exceptions, and Errors in Python**.

---

## 🧾 Problem Statement

Write a Python program that:

1. Takes user input and writes it to a file named `output.txt`.
2. Appends additional data to the same file.
3. Reads and displays the final content of the file.

---

## 📁 File

- `task2_write_append_file.py`

---

## 💻 How It Works

1. Prompts the user to enter initial data.
2. Saves that data into `output.txt` using write mode (`'w'`).
3. Prompts for more data to append.
4. Appends the new data using append mode (`'a'`).
5. Reopens the file in read mode (`'r'`) and displays all the content line by line.

---

## 🧪 Sample Output

```bash
Enter some data to write to file: 25
Enter more data to append to file: Hello

Final content of output.txt:
25
Hello

