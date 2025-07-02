# Document-Text-Extraction
Universal Document Text Extractor is a Python tool that extracts text from PDF, DOCX, and TXT files. It auto-detects the file type and displays the content directly in the output or terminal.

# 🧾 Universal Document Text Extractor

A smart Python-based utility to **extract and display text** from multiple document formats: **PDF**, **DOCX**, and **TXT** — all with a single click.

This tool is especially designed for **Google Colab**, making document analysis seamless for developers, students, and researchers. Whether you're reviewing reports or parsing documents for NLP tasks — this extractor gets the job done cleanly and efficiently.

---

## ✨ Features

✅ Supports multiple file types: `.pdf`, `.docx`, `.txt`  
✅ No need to manually type file names  
✅ Auto-detects file type and applies the right extraction method  
✅ Outputs clean, readable text directly in the notebook/terminal  
✅ 100% beginner-friendly & ready-to-run in Google Colab

---

## 📁 Supported File Types

| File Type | Description               | Library Used   |
|-----------|---------------------------|----------------|
| `.pdf`    | PDF files (text-based)    | `PyMuPDF`      |
| `.docx`   | Word documents             | `python-docx`  |
| `.txt`    | Plain text files           | Python I/O     |

---

## 🔧 Installation

Install required libraries (Colab or local):

```python
!pip install pymupdf python-docx
