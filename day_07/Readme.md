# 📊 Day 7 — Sales Data Analysis & Validation

## 🚀 90 Days of Data Analytics

**Day:** 7/90
**Status:** ✅ Completed
**Tool:** Microsoft Excel
**Focus:** Data Cleaning, XLOOKUP & Outlier Analysis

---

## 📌 Overview

On Day 7 of my 90-Day Data Analytics journey, I worked with a **Sales Dataset** in Microsoft Excel.

The main focus of this day was on practical data validation, using **XLOOKUP** to retrieve information from lookup tables, and identifying and evaluating potential outliers in the Sales and Profit columns.

The objective was not only to perform the calculations but also to understand the reasoning behind the decisions made during data analysis.

---

## 🎯 Objectives

The main objectives of Day 7 were:

* Understand and work with lookup tables.
* Use **XLOOKUP** to retrieve relevant information.
* Validate the results obtained through XLOOKUP.
* Analyze the Sales column for unusually high or low values.
* Analyze the Profit column for potential outliers.
* Understand that an extreme value is not automatically an outlier.
* Make appropriate decisions about handling potential outliers.

---

## 🛠️ Tools Used

* **Microsoft Excel**
* XLOOKUP
* Sorting & Filtering
* Basic statistical analysis
* Data validation
* Outlier analysis

---

## 🔎 1. XLOOKUP Validation

I worked with two lookup tables:

* `Orders_Lookup`
* `Product_Lookup`

I used **XLOOKUP** to retrieve the required information from these tables.

After applying the formulas, I manually checked the returned values against the corresponding lookup tables to verify that the results were correct.

### ✅ Validation Result

The XLOOKUP results from both:

* Orders Lookup
* Product Lookup

were checked and found to be **correct**.

This helped me understand the importance of validating lookup results instead of assuming that a formula has worked correctly just because it returns a value.

---

## 📈 2. Sales Column — Outlier Analysis

I analyzed the Sales column to identify unusually high values.

The largest Sales value was approximately:

**22,638.48**

However, there were multiple values close to this maximum.

Therefore, I did not automatically classify the maximum Sales values as outliers.

### 💡 Observation

A value being very large does not necessarily mean that it is an outlier.

If several observations have similarly high values and they are reasonable within the context of the dataset, they may represent genuine sales transactions rather than errors.

### ✅ Action Taken

The high Sales values were **not blindly removed**.

Instead, they were evaluated in the context of the overall dataset before deciding whether they should be treated as outliers.

---

## 💰 3. Profit Column — Outlier Analysis

The Profit column was also analyzed for potential extreme values.

Rather than deleting extreme observations immediately, I considered whether the values could represent genuine business transactions.

### Action Taken

Potential Profit outliers were reviewed and evaluated based on their relationship with the rest of the dataset.

The key principle followed was:

> **Do not remove an outlier simply because it is extreme. First determine whether it is an error, a valid observation, or a meaningful business case.**

---

## 🧠 Key Learning

### 1. XLOOKUP

I learned how XLOOKUP can be used to retrieve information from another table efficiently.

### 2. Data Validation

Using a formula is only one part of data analysis. The results should also be validated to ensure that the returned information is correct.

### 3. Outlier Analysis

One of the most important lessons from Day 7 was that:

**Extreme ≠ Outlier**

An unusually high or low value should be investigated before deciding whether to remove or modify it.

### 4. Business Context Matters

Statistical analysis should be combined with an understanding of the dataset and the business situation.

---

## 📊 Skills Practiced

| Skill                   | Status |
| ----------------------- | ------ |
| Excel Data Cleaning     | ✅      |
| XLOOKUP                 | ✅      |
| Lookup Table Validation | ✅      |
| Data Analysis           | ✅      |
| Outlier Identification  | ✅      |
| Outlier Evaluation      | ✅      |
| Analytical Thinking     | ✅      |

---

## 📂 Files Included

```text
Day-07/
│
├── README.md
├── Sales_dataset.xlsx
│
└── screenshots/
    ├── xlookup_orders.png
    ├── xlookup_products.png
    ├── sales_outliers.png
    └── profit_outliers.png
```

---

## 🎯 Day 7 Outcome

By the end of Day 7, I was able to:

* Work with lookup tables in Excel.
* Apply and validate XLOOKUP.
* Analyze Sales and Profit columns.
* Identify potential outliers.
* Evaluate whether extreme values should actually be considered outliers.
* Make data-driven decisions instead of blindly modifying the dataset.

---

## 🚀 Progress

**Days Completed:** 7/90 ✅

**Days Remaining:** 83

This journey is helping me build my Data Analytics skills through consistent daily practice and hands-on datasets.

---

## 🔜 Next Step

Continue with **Day 8** and build on the concepts learned so far.

> **Consistency over perfection. One day, one dataset, one new skill at a time.** 📊🚀
