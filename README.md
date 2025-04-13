# 🧹 Duplicate File Cleaner & Renamer – Vanilla JS

A lightweight utility app built with **Vanilla JavaScript** that helps organize files by removing duplicates and renaming the remaining files in alphabetical order. Once letters (A-Z) are exhausted, it continues naming with numbers (1, 2, 3...).

---

## 🔧 Features

- 📁 Accepts a file path input
- 🗑️ Detects and removes duplicate files based on name/content
- 🔤 Renames remaining files alphabetically: A, B, C... Z
- 🔢 If more files remain, continues with numbers: 1, 2, 3...
- 🧼 Keeps your directories clean and organized
- 💡 Simple and intuitive logic using Vanilla JS

---

## 🛠 Tech Stack

- **Language:** JavaScript (Vanilla)
- **Runtime:** Node.js (for file system operations)

---

## 📂 How It Works

1. You provide the directory path.
2. The script scans all files in that directory.
3. It removes any duplicates (based on filename/content).
4. It renames the files:
   - First using **A-Z**
   - Then continues using **1, 2, 3...** if there are more than 26 files

---

## ⚙️ Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/MohamedMootez/todo-list-app.git
   cd duplicate-cleaner
