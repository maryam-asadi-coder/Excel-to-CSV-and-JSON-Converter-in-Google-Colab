# Excel-to-CSV-and-JSON-Converter-in-Google-Colab
A simple Google Colab script to upload an Excel file, convert it to both CSV and JSON formats, and download the results — beginner-friendly and ideal for data science learning.

# 📊 Excel to CSV and JSON Converter in Google Colab

This Google Colab notebook allows you to:
- Upload any Excel `.xlsx` file
- Automatically convert it to both `.csv` and `.json` formats
- Download the output files directly to your device

> ✅ Beginner-friendly — Ideal for data science learners and anyone working with tabular data.

---

## 📁 How to Use

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run the first cell to upload your Excel file
3. The script reads the first sheet of your Excel file
4. It converts the data into:
   - `iran_electricity.csv`
   - `iran_electricity.json`
5. You can download both files with one click

---

## 🔧 Requirements
- `pandas` (comes pre-installed in Colab)
- `openpyxl` (for reading Excel)

---

## 📌 Notes
- Ensure your Excel file is structured (header row + data rows)
- `force_ascii=False` is used to support non-English characters (e.g. Persian, Arabic)

---

## 🇮🇷 آموزش فارسی

این اسکریپت برای افرادی که می‌خواهند فایل اکسل را به فرمت CSV و JSON تبدیل کنند طراحی شده:

1. فایل Excel خود را آپلود کنید
2. کد را اجرا کنید
3. خروجی را با فرمت‌های `CSV` و `JSON` دانلود کنید

> آموزش ساده برای علاقه‌مندان به یادگیری داده‌کاوی با Python

---

## 👩‍💻 Created by Maryam Asadi  
Feel free to fork, star, or share with friends 🌟
