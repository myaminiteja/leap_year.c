Leap Year Checker in C

A simple C program that checks whether a given year is a leap year or not.

Project Structure
leap-year-checker/
├── leap_year.c
├── README.md
├── output.txt
└── .gitignore

Features
Accepts a year from the user.
Checks whether the year is a leap year.
Handles invalid years.
Uses logical and modulo operators.
Beginner-friendly C program.
Leap Year Rule

A year is a leap year if:

It is divisible by 400, OR
It is divisible by 4 but not divisible by 100.
Examples
2024 → Leap year
2000 → Leap year
1900 → Not a leap year
2023 → Not a leap year
Requirements
C compiler such as GCC
Code editor or IDE
Git (optional, for uploading to GitHub)
How to Compile

Open the terminal inside the project folder and run:

gcc leap_year.c -o leap_year

How to Run
Windows
leap_year.exe

Linux/macOS
./leap_year

Sample Input
Enter a year: 2024

Sample Output
===== Leap Year Checker =====
Enter a year: 2024
2024 is a leap year.

Another Example
===== Leap Year Checker =====
Enter a year: 2023
2023 is not a leap year.

Concepts Used
printf()
scanf()
Variables
if-else
Modulo operator (%)
Logical OR operator (||)
Logical AND operator (&&)
Comparison operators
