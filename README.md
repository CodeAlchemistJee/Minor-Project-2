# 🎓 Student Information System (Python Console App)

![Python](https://img.shields.io/badge/python-3.8+-blue.svg)
![Concepts](https://img.shields.io/badge/Concepts-Data_Structures_%7C_Algorithms-success.svg)

A robust, interactive Python console application designed to manage, process, and analyze student academic records. Built entirely using Python's standard library, this project demonstrates foundational programming concepts including algorithmic problem-solving, data validation, string/number manipulation, and dictionary-based data management.

## 📑 Table of Contents
1. [Project Overview](#project-overview)
2. [Core Features](#core-features)
3. [Algorithmic Implementations](#algorithmic-implementations)
4. [Installation & Usage](#installation--usage)


## 🎯 Project Overview
This application allows users to dynamically input an unrestricted number of student records (Name, Roll Number, Age, and Marks across 5 subjects). It strictly validates user inputs to prevent crashes and ensures data integrity (e.g., marks must fall between 0 and 100). Once the data is collected, the program generates a comprehensive academic and algorithmic summary report for each student.

## ✨ Core Features
* **Dynamic Data Entry:** Prompts the user for the number of students to process, adapting the execution loop accordingly.
* **Robust Error Handling:** Utilizes `try-except` blocks and `while` loops to catch invalid inputs (e.g., entering text instead of numbers) without crashing the program.
* **Academic Analytics:** Automatically calculates Total Marks, Average Marks, Highest/Lowest Marks, and determines Pass/Fail status (Average $\ge$ 50).
* **Age Categorization:** Sorts students into "Child", "Teenager", or "Adult" classifications based on input parameters.
* **Bonus Mathematical Modules:** Includes standalone functions to generate Fibonacci sequences, find specific range multiples (3 and 5 between 100-200), and calculate prime numbers up to 100.

## 🧠 Algorithmic Implementations
To demonstrate logic and control flow, this project implements several custom algorithmic functions from scratch:
* `is_prime(num)`: Mathematical prime number verification using square root optimization.
* `is_palindrome(s)`: String manipulation to check if a student's name reads the same forwards and backwards (ignoring spaces/case).
* `reverse_roll_number(roll_no)`: Reverses the digits of an integer strictly using a mathematical `while` loop (modulo and floor division) rather than relying on Python string slicing.

## ⚙️ Installation & Usage

No external libraries or dependencies are required. 

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/Student-Information-System.git](https://github.com/yourusername/Student-Information-System.git)
   cd Student-Information-System
