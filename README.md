# 🧠 Plagiarism Checker

Ever wondered how similar two documents really are? This simple Python tool checks for content similarity between two text files and shows how much of one is "plagiarized" from the other.

## 📌 What It Does

- Reads two input text files
- Compares their content using Python's `difflib.SequenceMatcher`
- Calculates and prints the similarity as a percentage

## 🛠️ How It Works

We use Python’s built-in `SequenceMatcher` to find how closely the text in one file matches the other. It's not a full-fledged plagiarism detector but gives a quick estimate — great for simple use cases or learning string comparison logic.

## 🧪 Sample Use Case

You have:
- `demo1.txt` → Original content  
- `demo2.txt` → Possibly copied content

Run the script and it will tell you how similar the two are!

Example output:
The Plagiarized content is 74.56%

markdown

## ▶️ How to Run

1. Make sure Python is installed on your system.
2. Save your files as `demo1.txt` and `demo2.txt` in the same folder.
3. Run the script:

```bash
python plagiarism_checker.py

🔧 Requirements
No external libraries needed. Just Python 3+.

📂 Files Included
->plagiarism_checker.py – Main script
->demo1.txt – Sample text file
->demo2.txt – Sample text file

🚀 What's Next?
This is a basic version. You could enhance it by:

->Ignoring punctuation/case
->Adding a web interface
->Comparing multiple files in a folder

