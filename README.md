# Question Solution Mapper

## Overview

Question Solution Mapper is a Python-based automation tool that eliminates the manual process of taking screenshots and renaming question and solution images.

The system uses metadata available in an Excel file to map randomly named image files from a ZIP archive and automatically rename them into an organized format:

Q1.png, S1.png, Q2.png, S2.png ... etc.

This replaces a time-consuming manual workflow with a fully automated pipeline.

---

## Problem Statement

The content generation team receives:

1. PDF containing all questions and solutions
2. ZIP file containing question and solution images with random filenames
3. Excel file containing metadata about each question

Example:

Before:

QUES_ENG_axsmp57v00jnlju36fhcfw2y.png
SOLU_ENG_fgcc35vp5llm8gyvi540mdzs.png

After:

Q1.png
S1.png

The existing process required employees to manually take screenshots and rename every file.

This project automates the entire workflow.

---

## Solution

The application:

- Reads metadata from Excel
- Extracts question order information
- Maps random image filenames to their actual sequence
- Identifies corresponding solution images
- Renames files automatically
- Generates an organized output folder

Output Example:

Q1.png
S1.png
Q2.png
S2.png
Q3.png
S3.png

---

## Features

- Automatic Excel metadata processing
- ZIP archive handling
- Question-to-solution mapping
- Bulk file renaming
- Organized output generation
- Output ZIP creation
- Zero manual screenshot work

---

## Technologies Used

- Python
- Pandas
- ZipFile
- Pathlib
- OS Module
- File Handling

---

## Workflow

Excel Metadata
↓
Build Mapping Dictionary
↓
Read ZIP Images
↓
Match Question & Solution Files
↓
Rename Files
↓
Generate Output Folder
↓
Export Final ZIP

---

## Results

Successfully processed:

- 45 Questions
- 45 Solutions
- 90 Files Renamed
- 0 Manual Intervention

Generated Output:

Q1.png → Q45.png

S1.png → S45.png

---

## Project Structure

question-solution-mapper/

├── question_solution_mapper.ipynb

├── sample_data/

│ ├── Excelfile.xlsx

│ ├── Zipfile.zip

│

├── renamed_output/

│ ├── Q1.png

│ ├── S1.png

│ └── ...

│

└── README.md

---

## Future Improvements

- Convert notebook into production-ready Python package
- Add GUI interface
- Support multiple ZIP files
- Add validation reports
- Deploy as a web application

---

## Author

Khushi Yadav

Python | Data Analytics | Automation | Problem Solving
