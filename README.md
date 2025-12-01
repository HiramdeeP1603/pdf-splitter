
# 📄 PDF Splitter

![Language](https://img.shields.io/badge/Language-Python-blue?style=for-the-badge&logo=python)
![Platform](https://img.shields.io/badge/Platform-Google%20Colab-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
[![LinkedIn](https://img.shields.io/badge/HiramDeep%20Kaur-LinkedIn-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/hiram-deep-227916337/)

---

## 📌 Project Overview

This notebook is a **Python-based PDF splitter tool** built on Google Colab. It allows users to:

- Split a PDF at a specific page  
- Split a PDF into **individual pages**, each saved as a separate PDF file  
- Use `PyPDF2` library for PDF manipulation  
- Save outputs in a structured folder  

It is designed for **self-learning and practical experimentation** in Python.

---

## 🔗 Self-Learning Resource

[PyPDF2 Documentation](https://pypdf2.readthedocs.io/en/latest/)

---

## 📌 Features

### 1. Split PDF at a Specific Page

- Users can specify the page number to split the PDF.  
- Creates two separate PDFs:
  - `part1.pdf` → pages before the split  
  - `part2.pdf` → pages after the split  

**Example Usage:**
```python
split_pdf(input_pdf, output_dir, split_page)
````

---

### 2. Split Every Page into a Separate PDF

* Each page of the PDF is saved as a separate file: `page_1.pdf`, `page_2.pdf`, etc.

**Example Usage:**

```python
split_pdf(input_pdf, output_dir)
```

---

### 3. Folder Structure

```
PDF_Splitter/
├── PDF_Splitter.ipynb
└── README.md
```

---

### 4. Homework / Exercise

* Split every single page of a PDF and save it into a new PDF file.

---

## 👤 Author

**HiramDeep Kaur**
🔗 [LinkedIn Profile](https://www.linkedin.com/in/hiram-deep-227916337/)

---

⭐ If you found this notebook helpful, please **Star** the repository and share with others!

---
