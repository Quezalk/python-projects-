# 🧑‍💻 User Account Automation Script

This project is a Python automation script that simulates a real-world scenario of IT operations — automatically creating user accounts from a spreadsheet of new hires.

## 📌 Problem Statement

HR provides a CSV file (`users_in.csv`) containing a list of new employees without passwords. The IT department must generate secure passwords for each user, create accounts, and store the updated data for further use.

## ✅ What This Script Does

- Reads an input CSV with `username`, empty `password`, and `real_name`
- Generates a secure 16-character password for each user
- Simulates creating user accounts (prints confirmation for each user)
- Writes the updated information into a new output CSV (`users_out.csv`)

## 🛠 Technologies Used

- Python 3
- `csv` for file handling
- `secrets` for secure password generation
- `pathlib` for cross-platform file paths

## 🧾 Sample Input (`users_in.csv`)

```csv
username,password,real_name
amanda,,Amanda Alonso
ian,,Ian Ortega
eugene,,Eugene Konya
💾 Sample Output (users_out.csv)
csv
Copy
Edit
username,password,real_name
amanda,4b7f1a2ddabc9e34,Amanda Alonso
ian,29d19d8dcdc021f3,Ian Ortega
eugene,a1ddccf1aa25b84d,Eugene Konya
🚀 How to Run
Clone the repository

Open the .ipynb file or .py script

Run the cells or script in a Python environment

The output will be saved as users_out.csv in the same directory

📂 Files in This Repo
user_account_automation.ipynb: The Jupyter Notebook used in this project

users_in.csv: The input data file

users_out.csv: The output data with passwords

README.md: This file

✨ Result
This script automates a repetitive, time-consuming task — creating user accounts and generating passwords — saving hours of manual work.

📌 This project was part of my hands-on practice during a Python course on Coursera.


Let me know if you'd like to customize this more — for example, adding screenshots, your name, or course details.
