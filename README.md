# Automated Question Paper Generator Using AI
This code automates question paper creation by reading a .docx question bank, categorizing questions by units, and selecting them based on predefined norms. It generates a structured paper with 10 one-mark and 5 ten-mark questions, ensuring balanced unit coverage and proper formatting, saving it as a .docx file ready for use.



## Overview
The **Automated Question Paper Generator** is a Python-based tool designed to simplify the process of creating question papers. It analyzes an input question bank in `.docx` format, categorizes questions, and generates a formatted question paper adhering to predefined norms.

## Features
- **Input Parsing**: Reads questions from a `.docx` file.
- **Categorization**: Groups questions by units and difficulty.
- **Question Selection**: Selects questions based on:
  - Part A: 10 questions (2 per unit, 1 mark each).
  - Part B: 5 questions with internal choices (1 per unit, 10 marks each).
- **Output**: Generates a `.docx` file for the question paper.

## Methodology
1. **Document Parsing**: Extracts text from the input file using the `python-docx` library.
2. **Categorization**: Basic text classification groups questions by units.
3. **Selection Algorithm**: Ensures balanced selection based on the Bloom's  level.
4. **Output Formatting**: Generates a final question paper as a `.docx` file.

## Requirements
- Python 3.7+
- Libraries:
  - `python-docx`
  - `random` (built-in)

Install the required dependencies:
```bash
pip install python-docx
```
## Future Enhancements
1. Incorporate advanced NLP for better categorization.
2. Add support for Bloom's taxonomy levels.
3. Develop a GUI for non-technical users.


#### Feel free to contribute your ideas
