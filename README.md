# 🚀 Question Solution Mapper

> Turning a tedious manual workflow into a fully automated content-processing pipeline.

## 🎯 The Problem

Imagine receiving:

📄 A PDF containing all questions and solutions

📦 A ZIP file containing hundreds of images with random names

📊 An Excel sheet containing metadata

Example:

QUES_ENG_fgcc35vp5llm8gyvi540mdzs.png

SOLU_ENG_yh0nkd2ywd9bfp9utd4og9xz2.png

Employees were manually:

❌ Taking screenshots

❌ Renaming files one by one

❌ Organizing question and solution images

A process that was repetitive, error-prone, and time-consuming.

---

## 💡 The Idea

Instead of manually processing every file, why not use the metadata already present in the Excel sheet?

This project automatically:

✅ Reads Excel metadata

✅ Identifies question order

✅ Maps random image names

✅ Matches question images with solution images

✅ Renames files automatically

✅ Creates a clean structured output

---

## ⚙️ How It Works

```text
Excel Metadata
      │
      ▼
Build Mapping Dictionary
      │
      ▼
Read ZIP Archive
      │
      ▼
Match Image Names
      │
      ▼
Rename Files
      │
      ▼
Generate Organized Output
```

---

## 🔍 Example

### Before

```text
QUES_ENG_fgcc35vp5llm8gyvi540mdzs.png
SOLU_ENG_fgcc35vp5llm8gyvi540mdzs.png

QUES_ENG_yh0nkd2ywd9bfp9utd4og9xz2.png
SOLU_ENG_yh0nkd2ywd9bfp9utd4og9xz2.png
```

### After

```text
Q1.png
S1.png

Q2.png
S2.png
```

---

## 📈 Results

### Successfully Processed

| Metric | Value |
|----------|---------|
| Questions | 45 |
| Solutions | 45 |
| Total Files | 90 |
| Manual Screenshots | 0 |
| Renaming Accuracy | 100% |

---

## 🛠️ Tech Stack

- Python
- Pandas
- ZipFile
- Pathlib
- OS Module
- File Handling
- Data Processing

---

## 📂 Project Structure

```text
question-solution-mapper/

├── question_solution_mapper.ipynb
├── sample_data/
│   ├── Excelfile.xlsx
│   └── Zipfile.zip
│
├── renamed_output/
│   ├── Q1.png
│   ├── S1.png
│   ├── Q2.png
│   ├── S2.png
│   └── ...
│
└── README.md
```

---

## 🌟 Key Highlights

✔ Automated a real-world workflow

✔ Eliminated repetitive manual work

✔ Processed bulk files using metadata mapping

✔ Built a scalable file-renaming pipeline

✔ Demonstrated data processing and automation skills

---

## 🔮 Future Enhancements

- Build a GUI version
- Add drag-and-drop support
- Generate validation reports
- Convert into a Python package
- Deploy as a web application

---

## 👩‍💻 Author

**Khushi Yadav**

Passionate about Automation, Data Analytics, and Building Practical Solutions to Real Problems.

⭐ If you found this project interesting, feel free to explore the repository!
