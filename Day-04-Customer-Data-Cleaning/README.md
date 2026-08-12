# 📊 Day 4 — Customer Data Cleaning & Analysis

**90-Day Data Analytics Internship Preparation Journey**

On Day 4 of my 90-day Data Analytics journey, I worked on a customer dataset using Microsoft Excel.

The main focus of this project was **data inspection, data cleaning, transformation, filtering, sorting, and extracting meaningful insights from customer data.**

---

## 🎯 Objective

The objective of this project was to practice how a Data Analyst works with raw customer data before using it for analysis.

The workflow followed was:

**Raw Data → Data Inspection → Data Cleaning → Analysis → Insights**

---

## 🛠️ Tools Used

- Microsoft Excel
- Excel Filters
- Excel Sorting
- Flash Fill
- Text to Columns
- Duplicate Checking
- Data Cleaning
- Basic Data Analysis

---

## 📂 Dataset

The dataset contains **5,000 customer records**.

Important fields used in the analysis include:

- Customer ID
- Full Name
- Age
- Gender
- Email
- Phone
- City
- State
- Registration Date
- Preferred Channel

---

## 🔍 Tasks Performed

### 1. Data Inspection

I inspected the raw customer data to identify potential data-quality issues such as:

- Missing values
- Duplicate customer information
- Duplicate email records
- Missing contact information
- Missing preferred channels
- Inconsistent formatting

---

### 2. Data Cleaning & Transformation

I practiced:

- Removing unnecessary columns from the working dataset
- Standardizing text formatting
- Cleaning spaces
- Standardizing email formatting
- Splitting names into First Name and Last Name
- Converting registration dates into a consistent date format

> Note: I did not blindly delete blank values or duplicate records. I first identified and documented them because missing or duplicate data requires proper investigation before deciding how it should be handled.

---

### 3. Flash Fill

I used **Flash Fill** to extract useful information from the `Full_Name` column.

Example:

`Full_Name → First_Name + Last_Name`

---

### 4. Text to Columns

I practiced using **Text to Columns** to split data based on its structure.

---

### 5. Sorting & Filtering

I used Excel sorting and filtering to answer questions such as:

- Which customers are above age 40?
- Which customers registered after January 1, 2025?
- Which city has the highest number of customers?
- Which preferred communication channel is most common?

---

# 📈 Key Insights

| Question | Answer |
|---|---:|
| Total customers | 5,000 |
| Customers above age 40 | 1,490 |
| Customers registered after Jan 1, 2025 | 1,348 |
| Customers with missing preferred channel | 114 |
| Duplicate email records identified | 156 |
| Most common preferred channel | Online |
| City with the most customers | Sacramento |

---

## 🧠 Key Learnings

The biggest lesson from Day 4 was:

> **Data analysis starts with understanding and preparing the data correctly.**

I learned that data cleaning is not simply about deleting blanks or duplicates.

Before modifying data, a Data Analyst should ask:

- Is this actually a duplicate?
- Why is this value missing?
- Will deleting this record affect the analysis?
- What does this field represent?
- Is the data format consistent?

This helped me understand the importance of **data quality and validation before analysis.**

---

## 📸 Project Screenshots

The `screenshots` folder contains selected screenshots of:

1. Data Inspection
2. Cleaned Data
3. Final Insights

---

## 📁 Project Structure

```text
Day-04-Customer-Data-Cleaning/
│
├── Day4_Customer_Data_Cleaning_Analysis.xlsx
├── README.md
│
└── screenshots/
    ├── data_inspection.png
    ├── cleaned_data.png
    └── final_insights.png
