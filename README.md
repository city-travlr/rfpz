
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://blank-app-template.streamlit.app/)

### How to run it on your own machine

# RFP to PowerPoint Generator

This project helps you transform RFP documents into professional PowerPoint presentations using NLP and automation.

---

## **Features**
- Extracts text and key information from uploaded RFP PDFs.
- Summarizes key sections like goals, deliverables, and timelines.
- Generates a fully customizable PowerPoint presentation.

---

## **Getting Started**

### **1. Install Requirements**
Make sure you have Python 3.9+ installed. Then, install the necessary dependencies:

```bash
pip install -r requirements.txt
python -m spacy download en_core_web_sm


streamlit run /workspaces/rfpz/app/main.py
