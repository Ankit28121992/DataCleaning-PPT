# 📊 SQL Data Cleaning Project by Ankit

This repository contains a PowerPoint presentation prepared by **Ankit**, showcasing two practical data cleaning projects using **MySQL**.

---

## 📁 Contents

- `Data_Cleaning_Project_Ankit.pptx` – PowerPoint presentation explaining:
  - SQL queries for cleaning the data
  - Steps taken to fix data issues
  - Final conclusion and recommendation

---

## 🧹 Project Overview

The project demonstrates cleaning of a sample employee table named `practice` from the `my_project` database. The following steps were taken:

### 1️⃣ Filling Missing Data
- Replaced empty strings in `name`, `phone`, `hire_date`, and `status` columns with `NULL`.

### 2️⃣ Fixing Incorrect Data
- Phone number with letters (`98765abc`) was set to `NULL`.
- Negative salary (`-70000`) was corrected to a valid amount (`70000`).
- Incorrect email format (`janesmith@emailcom`) was updated.

### 3️⃣ Removing Duplicate Records
- Identified duplicate `emp_id` records using `GROUP BY` and `HAVING`.
- Removed extra duplicate entry using `DELETE`.

---

##  Summary

- ✅ Missing values cleaned.
- ✅ Invalid entries corrected.
- ✅ Duplicate rows handled.
- ✅ Final table is clean and ready for analysis.

---

##  Tools Used

- **MySQL Workbench** – For running SQL queries.
- **MS PowerPoint** – For creating the presentation/report.

---

## 🙋‍♂️ About the Author

- 👤 **Name:** Ankit  
- 🎓 Interest in SQL, data cleaning, and analytics  
- 💡 Passionate about learning and presenting real-world database projects

---

## 📬 Contact

Feel free to reach out for feedback or suggestions.  
Let’s make data cleaner and smarter, together! 😊
