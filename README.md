# 🧮 Mini Project 7 - Marks Adding

This project reads a CSV file containing student roll numbers and marks, adds the marks for each roll number, and saves the total in a new CSV file.

## 📌 What It Does
- Reads input file with duplicate roll numbers
- Sums up marks for each roll number
- Prints the result
- Saves it to `Output_Marks.csv`

## 🛠️ Tech Used
- Python
- pandas library

## ▶️ How to Run
1. Make sure `pandas` is installed (`pip install pandas`)
2. Place your CSV file in the same folder
3. Run the script

## 📁 Example File Format

| Roll Num | Marks |
|----------|--------|
| 101      | 20     |
| 102      | 25     |
| 101      | 30     |

➡️ Output will be:

| Roll Num | Marks |
|----------|--------|
| 101      | 50     |
| 102      | 25     |

