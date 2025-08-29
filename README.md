📝 PAN Number Validation Project

This project focuses on cleaning and validating PAN (Permanent Account Number) data for Indian nationals. The objective is to ensure all PAN numbers follow the official format and are categorized as Valid or Invalid.

📌 Project Objectives

Clean and preprocess PAN number dataset.
# 📝 PAN Number Validation Project Using Python  

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)  
![Pandas](https://img.shields.io/badge/Library-Pandas-green)  
![Excel](https://img.shields.io/badge/Data-Excel-lightgrey)  
![License: MIT](https://img.shields.io/badge/License-MIT-yellow)  

This project focuses on **cleaning and validating PAN (Permanent Account Number) data** for Indian nationals.  
The aim is to ensure that each PAN number follows the **official format** and is categorized as **Valid** ✅ or **Invalid** ❌.  

---

## 📌 Features
- Data cleaning & preprocessing  
- PAN number format validation  
- Categorization: ✅ Valid | ❌ Invalid  
- Summary report with statistics  
- Export results to Excel  

---

## ⚙️ Validation Rules
A valid PAN number must:  
1. Be exactly **10 characters** long.  
2. Follow the format: **AAAAA1234A**  
   - First 5 → Alphabets (A–Z)  
   - Next 4 → Digits (0–9)  
   - Last 1 → Alphabet (A–Z)  
3. Additional Rules:  
   - 🚫 No identical adjacent alphabets (e.g., `AABCD`)  
   - 🚫 No sequential alphabets (e.g., `ABCDE`)  
   - 🚫 No identical adjacent digits (e.g., `1123`)  
   - 🚫 No sequential digits (e.g., `1234`)  

✅ Example of Valid PAN → `AHGVE1276F`  
❌ Example of Invalid PAN → `ABCDE1234Z`  

---

## 📊 Output & Report
The program generates:  
- 📌 Total records processed  
- ✅ Count of Valid PANs  
- ❌ Count of Invalid PANs  
- 🚫 Missing / Incomplete PANs  

All results are saved to:  
📄 **PAN_Validation_Output.xlsx**  

---

## 🛠 Tech Stack
- **Python 3.8+**  
- **Pandas** (Data Cleaning)  
- **Regex** (Pattern Matching)  
- **OpenPyXL** (Excel I/O)  

---

## 🚀 Getting Started  

### 1️⃣ Clone Repository  
```bash
git clone https://github.com/Chinni-2005/Pan-Number-Validation-Project-Using-Python.git
cd Pan-Number-Validation-Project-Using-Python

Validate PAN numbers based on government rules.

Categorize PANs into:

✅ Valid PAN

❌ Invalid PAN

Generate a summary report.

⚙️ Data Cleaning Steps

Handle missing values (remove or impute).

Remove duplicates.

Trim leading/trailing spaces.

Convert PANs to uppercase.

🔍 PAN Validation Rules

A valid PAN number must:

Be exactly 10 characters long.

Follow the format: AAAAA1234A

First 5 → Alphabets (uppercase).

Next 4 → Digits.

Last 1 → Alphabet (uppercase).

Rules for validation:

No adjacent identical characters (alphabets or digits).

First 5 alphabets cannot form a sequence (e.g., ABCDE, BCDEF).

4 digits cannot form a sequence (e.g., 1234, 2345).

✅ Example of Valid PAN → AHGVE1276F
❌ Example of Invalid PAN → ABCDE1234Z

📊 Output & Report

The program generates:

Total records processed

Count of Valid PANs

Count of Invalid PANs

Missing or incomplete PANs (if applicable)

🛠️ Tech Stack

Python / SQL (can be used for validation logic)

Pandas / Regex (for data cleaning & validation)

📜 License

This project is licensed under the MIT License – feel free to use and modify.
