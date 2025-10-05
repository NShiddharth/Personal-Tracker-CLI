Project Overview

The Personal Tracker CLI is a lightweight, command-line tool that helps users manage their habits, tasks, and expenses efficiently.
It allows users to add, list, update, delete, and summarize daily entries, all stored persistently in a simple text file named tracker.txt.

The project is implemented using only the Python standard library and includes complete input validation to ensure smooth operation without crashes.

Features

Add a new habit, task, or expense (with an optional amount)

List all items in a clear, tabular format

Update or delete existing entries

View a quick summary (total habits, tasks, and total expense in ₹)

Automatically saves data to a file (tracker.txt)

Handles invalid inputs gracefully

Simple and user-friendly interface

File Structure
Personal_Tracker/
│
├── tracker.py        # Main Python script
├── tracker.txt       # Data file (auto-created on first run)
└── README.md         # Project documentation

File Format Description

File Name: tracker.txt
Format: Each line represents one record, with fields separated by the | character.

DATE|CATEGORY|DESCRIPTION|AMOUNT


Example:

2025-10-04|Habit|Morning Yoga|0.00
2025-10-04|Task|Complete Project Report|0.00
2025-10-04|Expense|Groceries|250.00

How to Run
Step 1: Ensure Python 3 is Installed

Check your Python version:

python3 --version

Step 2: Run the Program

Navigate to the folder containing tracker.py and execute:

python3 tracker.py

Step 3: Choose Options from the Menu

Example interaction:

==== PERSONAL TRACKER ====
1. List all items
2. Add new item
3. Update existing item
4. Delete an item
5. View summary
6. Exit

Choose an option (1–6): 2
Enter category (habit/task/expense): expense
Enter description: Snacks
Enter amount (optional): 50
Added successfully!

Step 4: Exit and Auto-Save

When you exit using option 6, your data is automatically saved to tracker.txt.

Input / Output Example

Input (via CLI):

Add → Expense → “Lunch” → ₹120

Add → Habit → “Read 10 pages of a book”

Output (tracker.txt):

2025-10-04|Expense|Lunch|120.00
2025-10-04|Habit|Read 10 pages of a book|0.00

Summary Example
Summary:
------------------------------
Total Habits : 2
Total Tasks  : 1
Total Expense: ₹520.00
------------------------------
