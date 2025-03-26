# Scrabble-Word-Project
This project involves writing a program that takes the letter combination “tabind” and generates an alphabetical list of all words that can be formed using these letters, based on a provided Scrabble dictionary. This project requires: **Python 3.x**

**Understanding the Problem Statement**

You have a set of letters: "tabind"

You have a Scrabble dictionary (a file containing a list of valid words)

Your goal is to find all words that can be formed using only these letters and display them in alphabetical order.

**Rules & Constraints:**
You can only use letters from "tabind" (each letter can be used only as many times as it appears in "tabind").

The words must be valid Scrabble words (found in the provided dictionary file).

The final output must be sorted alphabetically.

****
**To solve this problem, you need to follow these steps**:

**Step 1**: Read and Load the Scrabble Dictionary

The dictionary is provided in a text file ( NSWL2023.txt).

Each word is written on a separate line.

Your program will read these words into memory.

**Step 2**: Check Which Words Can Be Formed from "tabind"

Use the Counter data structure (from Python’s collections module) to count letter occurrences efficiently.

For each word in the dictionary:

Count the letters in the word.

Check if it can be formed using the letters from "tabind" without exceeding the available counts.

**Step 3**: Sort the Valid Words Alphabetically
Use Python’s built-in sorted() function to arrange the valid words alphabetically.

**Step 4**: Display or Save the Results
The results can be displayed in tabular format (if using Jupyter Notebook).

✔ Read Scrabble dictionary

✔ Filter words that can be formed using "tabind"

✔ Sort and display/save the results

✔ Optimizations for user input, performance, and scoring
