# 📊 Social Media Data Scraping & Translation Tool

A Python-based tool for **scraping, translating, and consolidating** social media content from multiple platforms including **Twitter**, **Instagram**, **Facebook**, and **Reddit**. The extracted data includes user-generated posts and comments related to public opinions, complaints, suggestions, or feedback.

Developed by **Eng. Tamer Mohamed Elsaqa**

---

## 📌 Project Features

✅ Scrapes data from:
- 🐦 **Twitter** using SerpApi
- 📸 **Instagram** using SerpApi
- 📘 **Facebook** using SerpApi
- 👽 **Reddit** using PRAW API

✅ Extracts detailed metadata:
- Post/Comment text  
- **Translation** (English ⇄ Arabic)  
- **Date** & **Time**  
- **Original Language**  
- **Source Platform**  
- **Direct Link**

✅ Exports everything into a **clean, structured Excel sheet**.

---

## ⚙️ Tech Stack

- `Python`
- [`SerpApi`](https://serpapi.com/) (Twitter, Instagram, Facebook)
- `PRAW` (Reddit API)
- `langdetect` (Language Detection)
- `DeepL API` or `Google Translate API` (for Translation)
- `Pandas` (for Excel export)
- `openpyxl`

---

## 📁 Output Structure

The final Excel sheet contains the following columns:

| Text | Translated_Text | Date | Time | Language | Platform | Link |
|------|------------------|------|------|----------|----------|------|

---

## 🚀 How to Run

1. Install dependencies:

```bash
pip install pandas praw serpapi langdetect openpyxl

