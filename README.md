# DSA 2026 Entry Challenge

This repository contains my complete solution to the **Data Science Africa 2026 Entry Challenge**.

---

## 📌 Overview

The notebook is structured into three main sections:

1. Data Analysis (E1–E5)
2. Natural Language Processing (N1–N3)
3. Machine Learning & Visualization (M1–M4)

All grader checks pass successfully.

---

# 📊 1. Data Analysis

### E1 – Load Dataset
- Loaded Excel file using pandas
- Dataset shape: (158, 28)

### E2 – Reshape to Long Format
- Used `pd.melt()`
- Final shape: (4266, 4)

### E3 – Date Conversion
- Converted strings like `dec-20`
- Output type: `datetime64[ns]`

### E4 – CPI Filtering
Extracted:
- All Items CPI
- Core CPI
- Food CPI
- EFU CPI

### E5 – Missing Values
- Replaced missing values with median per indicator
- Missing values after processing: 0

---

# 🧠 2. Natural Language Processing

All tasks implemented using only built-in Python libraries.

### N1 – Word Frequency Counter
- Case-insensitive
- Ignores punctuation

### N2 – Sentence Extraction
- Returns sentences containing keywords

### N3 – Jaccard Similarity
- Computes intersection/union of word sets

---

# 📈 3. Machine Learning & Visualization

### M1 – Scatter Plot
- Visualized 2-class dataset
- Red: Class 0
- Blue: Class 1

### M2 – Separating Line
- Added diagonal boundary

### M3 – Gaussian Fitting
- Computed means
- Computed covariance matrices

### M4 – Heatmap Overlay
- Used multivariate Gaussian PDFs
- Overlaid contour plots


# ✅ Results

All `grader.check()` cells pass successfully.

Notebook is ready for submission.

## Author
Habeeb Olakunle Sanni
Sannihabeebo30@gmail.com
