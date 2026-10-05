# CSC649 Setup & First Python Experiment

## Description
This program is a simple text analyzer written in Python. It takes a user-provided sentence and displays:
- Total word count
- Total character count (including spaces)
- A warning message if the input is empty or consists only of whitespace.

## How to Run
1. Open the project in **PyCharm**.
2. Ensure the Python 3.12 virtual environment (`.venv`) is selected.
3. Open `main.py` and run it (`Shift + F10` or click **Run**).
4. Enter a sentence when prompted in the terminal.

## Test Results
1. **Normal Sentence (`Hello world from Python`):**
   - Output: `Word count: 4`, `Character count (including spaces): 22`
2. **Empty Input (Pressing Enter / Whitespace):**
   - Output: `You did not enter a sentence.`
3. **Sentence with Extra Spaces (`  Extra   spaces  test  `):**
   - Output: `Word count: 3`, `Character count (including spaces): 23`

## Limitations
- The character count includes leading, trailing, and intermediate spaces. It does not separate letters from punctuation marks or whitespace.