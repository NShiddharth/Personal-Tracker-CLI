🧭 Personal Tracker CLI

A simple and powerful Command-Line Interface (CLI) application built in Python to help you track habits, daily tasks, and expenses — all from your terminal!
Your personal productivity companion that keeps everything organized in one place.

🌟 Features

✅ Add New Entries

Quickly add habits, daily tasks, or expenses using simple commands.

✅ View Records

Instantly display all your recorded items in a clean, readable format.

✅ Data Persistence

All records are automatically saved in tracker.txt so your data never gets lost.

✅ Interactive Menu

Easy-to-use menu-driven interface with numbered options.

✅ Error Handling

Input validation ensures you only enter valid options and data.

✅ Customizable

You can easily extend it to include new categories (like goals, notes, etc.).

🛠️ Technologies Used

🐍 Python 3

🗃️ File I/O (tracker.txt for data storage)

💡 Datetime module for automatic timestamps

📂 Project Structure
Personal_Tracker/
│
├── tracker.py          # Main script file
├── tracker.txt         # Data file (auto-created)
└── README.md           # Documentation

🚀 How to Run the Project
Step 1: Clone the Repository
git clone https://github.com/yourusername/Personal-Tracker-CLI.git

Step 2: Navigate to the Project Folder
cd Personal-Tracker-CLI

Step 3: Run the Program
python tracker.py

🧑‍💻 Usage Guide

Once you run the script, you'll see an interactive menu like this:

📘 Personal Tracker CLI 📘

1. View all records
2. Add a new habit/task/expense
3. Delete an entry
4. Clear all records
5. Exit

Choose an option (1-5):

Example Interaction
Choose an option (1-5): 2
Enter the type (habit/task/expense): habit
Enter description: Morning Run
Entry added successfully!


Your data is automatically saved to tracker.txt:

[2025-10-04 08:45] (HABIT): Morning Run

🧹 Optional Commands (Advanced Users)

You can reset or inspect data manually:

# View all data
cat tracker.txt

# Clear all data
echo "" > tracker.txt

📈 Future Enhancements

🔹 Add data visualization (charts using matplotlib)
🔹 Implement category-based summaries
🔹 Add export to CSV or Excel
🔹 Create a web or mobile version using Flask or Kivy
