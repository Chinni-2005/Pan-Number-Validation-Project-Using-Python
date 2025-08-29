📝 PAN Number Validation Project

This project focuses on cleaning and validating PAN (Permanent Account Number) data for Indian nationals. The objective is to ensure all PAN numbers follow the official format and are categorized as Valid or Invalid.

📌 Project Objectives

Clean and preprocess PAN number dataset.

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
