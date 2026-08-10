# Python Chapter 1 – Basic Programs

This repository contains basic Python programs created while learning the fundamentals of Python programming.

## 📌 Programs Included

### 1. Hello World

**File:** `01_hello.py`

A simple Python program that prints "Hello World" to the console.

```python
import os

print("Hello World")

File: 02_pr_01_twinkle.py
2. Twinkle Twinkle Little Star:

This program prints the lyrics of "Twinkle Twinkle Little Star" using a multi-line string.

print('''Twinkle Twinkle Little Star,
How I Wonder What You Are!
Up Above The World So High,
Like A Diamond In The Sky.''')

File: 03_pr_03_module_usage.py
3. Module Usage – Play Sound

This program demonstrates how to use the playsound module to play an audio file.

from playsound import playsound

playsound('D:\\MyData\\Business\\code playground\\Python Course With Notes\\1. Chapter 1\\play.mp3')

Note: Update the audio file path according to your computer before running the program.

4. List Directory

File: 04_pr_04_list_direcrory.py

This program uses Python's built-in os module to display the files and folders in the current directory.

import os

print(os.listdir())
🛠️ Technologies Used
Python
os module
playsound module
📂 Project Structure
Python-Chapter-1/
│
├── 01_hello.py
├── 02_pr_01_twinkle.py
├── 03_pr_03_module_usage.py
├── 04_pr_04_list_direcrory.py
└── README.md
🚀 How to Run
1. Install Python

Make sure Python is installed on your computer.

Check your Python version:

python --version
2. Clone the Repository
git clone <your-repository-url>
3. Open the Project Folder
cd Python-Chapter-1
4. Run a Python Program
python 01_hello.py

You can also run the other programs:

python 02_pr_01_twinkle.py
python 03_pr_03_module_usage.py
python 04_pr_04_list_direcrory.py
📦 Installing Playsound

The 03_pr_03_module_usage.py program uses the playsound package.

Install it using:

pip install playsound

Make sure the audio file path in the program points to a valid .mp3 file.

🎯 Learning Objectives

These programs demonstrate basic Python concepts:

Printing output
Working with strings
Using multi-line strings
Importing Python modules
Using the built-in os module
Listing files and directories
Installing and using external Python packages
Playing audio files using Python
📚 Programs Summary
File	Concept
01_hello.py	Hello World / Basic Output
02_pr_01_twinkle.py	Multi-line Strings / Printing
03_pr_03_module_usage.py	Module Import / Audio Playback
04_pr_04_list_direcrory.py	os Module / Directory Listing

👨‍💻 Author
Anish
