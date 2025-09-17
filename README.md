# File Handling and Exception Handling Assignment

## 📄 Description
This Python project demonstrates **file handling** and **exception handling** concepts. The program reads text from an input file, processes the content by converting it to **uppercase** and counting the **number of words**, and writes the processed content to a new output file. It also handles potential errors gracefully using **exception handling**.

---

## 📁 Project Files
- **`input.txt`** – Input file containing at least five lines of text.  
- **`file_processor.py`** – Python script that reads `input.txt`, processes the text, and writes results to `output.txt`.  
- **`output.txt`** – Output file created automatically by the script containing the processed text and word count.  

---

## ⚡ Features
- Reads content from `input.txt`.
- Counts the number of words in the text.
- Converts all text to uppercase.
- Writes the processed text and word count to `output.txt`.
- Handles errors such as missing input file or empty input gracefully.
- Professional and user-friendly output formatting.

---

## 🛠 How to Run
1. Make sure Python 3 is installed on your system.
2. Ensure `input.txt` exists in the same folder as the script with some text.
3. Open a terminal/command prompt and navigate to the project folder.
4. Run the script:

```bash
python file_processor.py


5. After successful execution, `output.txt` will be created automatically with the processed content.

---

## 📝 Example

**Content of `input.txt`:**

```
Python is a powerful programming language.
It is widely used in web development, data analysis, and AI.
File handling is an essential skill in Python.
Exception handling helps manage errors gracefully.
Always write clean and readable code.
```

**Content of `output.txt` after running the script:**

```
=== PROCESSED TEXT ===
PYTHON IS A POWERFUL PROGRAMMING LANGUAGE.
IT IS WIDELY USED IN WEB DEVELOPMENT, DATA ANALYSIS, AND AI.
FILE HANDLING IS AN ESSENTIAL SKILL IN PYTHON.
EXCEPTION HANDLING HELPS MANAGE ERRORS GRACEFULLY.
ALWAYS WRITE CLEAN AND READABLE CODE.

=== WORD COUNT: 29 ===
```

---

## 🚀 Notes

* The script automatically handles missing input files with a user-friendly error message.
* Empty input files are detected and a warning is printed.
* Output formatting includes clear headers and word count for professionalism.

---
```
## 📂 Project Folder Structure
```
Project_Files/
│── README.md
│── input.txt
│── file_processor.py
│── output.txt (sample)


```
