# 🎓 Certificate IEEE WIE UFPB Generator Automation (Google Colab / Streamlit – Raw Version)

This project is an **automation for generating certificates in PDF format**, built in **Python**, designed to generate certificates **in bulk** based on data stored in **Google Sheets**.

⚠️ **Important notice**  
This repository contains a **raw / early version** of the certificate generator logic.  
It is the **automation backbone** that later evolved into a **Streamlit-based application**.

The focus here is **process automation**, not final UI polish.

---

## 🤖 Project Nature

- ✅ **Automation-focused**
- ✅ Backend / processing logic
- ⚠️ Minimal UI (Colab / early Streamlit)
- 🧪 Prototype / MVP version

This code represents the **core engine** responsible for:
- reading participant data
- generating personalized certificates
- exporting PDFs automatically

---

## ✨ Features

- 📄 Uses a **PDF certificate template**
- 📊 Reads participant data from **Google Sheets**
- ✍️ Dynamically inserts:
  -| Nome do Aluno | Tipo do Evento | Tipo de Participante | Local do Evento | Data do Evento | Duração |
- 🧾 Generates **one PDF per participant**
- ☁️ Automatically saves files to **Google Drive**
- ⚙️ Runs entirely on **Google Colab**
- 🧱 Serves as the **raw version of the Streamlit generator**

---

## 🧰 Tech Stack

- **Python 3**
- **Google Colab**
- **PyPDF2** – PDF reading and writing
- **ReportLab** – PDF text rendering
- **Google Sheets API** (`gspread`)
- **Google Drive API**

---

## 📦 Required Libraries

Install the required libraries in Google Colab:

```python
!pip install PyPDF2
!pip install reportlab

## 🌐 Language

⚠️ The system is currently available in Portuguese only.

