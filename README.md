# 📘 Personal Data Collector --- Detailed README

Welcome to the **Personal Data Collector** project!\
This repository contains a Python program designed to collect personal
input from the user and display detailed information about each input
including its data type and memory address. It also performs a simple
calculation to estimate the user's birth year.

------------------------------------------------------------------------

## 📜 Overview

This project is ideal for **beginners learning Python**, especially
those wanting to understand:

-   How to take user input\
-   How to convert data types\
-   How to display type information\
-   How Python stores variables in memory\
-   Basic arithmetic operations\
-   Simple f-strings formatting

The program interacts with the user in real-time and prints a summary of
the collected data.

------------------------------------------------------------------------

## 🎯 Objectives of This Project

-   Demonstrate Python input/output operations\
-   Show how to use `int()` and `float()` for type conversion\
-   Teach how to access memory addresses using `id()`\
-   Provide a beginner-friendly demonstration of f-strings\
-   Implement a basic calculation (birth year estimation)

------------------------------------------------------------------------

## 🧩 Program Workflow

1.  User is welcomed with a message.\

2.  Script asks for:

    -   Name (string)\
    -   Age (integer)\
    -   Height in meters (float)\
    -   Favourite number (integer)\

3.  After receiving all inputs, the program:

    -   Displays the values\
    -   Shows type and memory address of each variable\

4.  Calculates estimated birth year:

        birthday = 2025 - age

5.  Ends with a thank‑you message.

------------------------------------------------------------------------

## 📂 Full Python Code

``` python
print("welcome to the interactive personal data collector!")


print("\n***************")


name = input("Please enter your name:")

age = int(input("Please enter your age:"))

height = float(input("Please enter your height:"))

number = int(input("Please enter your number:"))

print("\n***************")


print("Thank you! Here is the information We collected!")


print(f" Name:{name}(Type: {type(name)},Memory Address:{id(name)}")

print(f" Age:{age}(Type: {type(age)},Memory Address:{id(age)}")

print(f" Height:{height}(Type: {type(height)},Memory Address:{id(height)}")

print(f" Number:{number}(Type: {type(number)},Memory Address:{id(number)}")



birthday = 2025-age



print(f" Your birth year is approximat year:{birthday}(based on year age of {age})")



print("Thank you for using the personal Data Collector.Goodbye!")

      

```

------------------------------------------------------------------------

## ▶️ How to Run the Program

Make sure Python 3 is installed.

``` bash
python file1.py
```

------------------------------------------------------------------------

## 📦 Project Structure

    📁 Personal-Data-Collector
    │── First_project Foundamental.py
    │── README.md

------------------------------------------------------------------------

## 📘 Future Improvements (Optional)

Here are some ideas you can add later:

-   GUI interface using Tkinter\
-   Store data in a file\
-   Add validation for numeric inputs\
-   Improve the birth year calculation using actual current year\
-   Create a web version using Flask

------------------------------------------------------------------------

## 👤 Author

Created by **Jayal S Gorajiya**\
Feel free to contribute or request additional features!

------------------------------------------------------------------------


