# 📊 Day 5 — Retail Sales Analysis

**90-Day Data Analytics Journey**

On Day 5 of my 90-day Data Analytics journey, I revisited a retail sales dataset and performed an independent analysis using the Excel concepts I had learned so far.

The main goal of Day 5 was to test whether I could take raw data, understand it, analyze it, ask my own questions, and convert the results into meaningful business insights — without learning a new Excel concept just for the challenge.

---

## 🎯 Objective

The objective of this challenge was to practice:

- Understanding the structure of a dataset
- Identifying numerical and categorical variables
- Calculating revenue and sales metrics
- Using sorting and filtering
- Analyzing product, region, customer and payment information
- Performing month-wise and product-wise analysis
- Finding business patterns
- Developing business insights
- Creating my own analytical question

---

## 🛠️ Tools & Concepts Used

- Microsoft Excel
- Excel formulas
- Sorting
- Filtering
- Data Inspection
- Data Validation
- Conditional Formatting
- Text to Columns
- Flash Fill
- Basic data analysis
- Business insight generation

> I intentionally did not use Pivot Tables, Slicers, KPI Cards or Excel Dashboards because I have not learned those concepts yet. I wanted Day 5 to test the skills I had already learned.

---

# 📂 Dataset

The dataset contains retail order information including:

- Order ID
- Order Date
- Year
- Quarter
- Product Name
- Category
- Region
- Customer Type
- Payment Method
- Quantity
- Unit Price

### Data Grain

Each row represents **one order/transaction**.

---

# 🔍 Part 1 — Data Understanding

I first inspected the dataset and identified the different types of variables.

### Numerical Variables

- Quantity
- Unit Price

### Categorical Variables

- Product Name
- Region
- Customer Type
- Payment Method
- Category

### Time-related Variables

- Order Date
- Year
- Quarter

I also created my own business questions based on the available data.

---

# 📈 Part 2 — Analysis

I answered several business questions using the available Excel concepts.

| Question | Result |
|---|---:|
| Total Revenue | ₹28,220,731 |
| Highest Revenue Category | Electronics — ₹21,147,806 |
| Highest Revenue Region | Pune — ₹7,497,723 |
| Highest Revenue Customer Type | New — ₹10,578,194 |
| Most Frequently Used Payment Method | UPI |
| Highest Revenue Month | February — ₹2,662,308 |

---

# 💡 Part 3 — Business Insights

## 1. Yearly Sales Performance

2023 recorded the highest sales, while 2026 recorded the lowest sales among the years analyzed.

This indicates significant variation in yearly sales performance. Further analysis of promotions, seasonal trends, product demand and customer behavior could help identify the factors contributing to this difference.

---

## 2. Product Sales Performance

Watch had the highest sales volume with **468 units**, followed by Water Bottle with **466 units**. Book had the lowest sales volume with **405 units** among the products analyzed.

The business could investigate what factors contribute to stronger demand for high-performing products and explore cross-selling or promotional opportunities.

---

## 3. Customer Behavior

For Backpack and Water Bottle, Premium customers generated **₹262,588** in total revenue, while Returning customers generated **₹231,235**.

Premium customers therefore generated **₹31,353 more revenue** for these products.

This could be investigated further to understand Premium customers' purchasing behavior and to test targeted offers or product bundles.

---

# ⭐ Part 4 — My Own Analytical Question

Instead of only answering predefined questions, I created my own analysis:

### Question

**Which month has the highest and lowest quantity sold for each product?**

### Method

I analyzed:

- Product Name
- Month
- Quantity

I compared the quantity sold for each product across different months.

### Example Finding

For **Backpack**:

- Highest quantity sold: **May — 45 units**
- Lowest quantity sold: **January — 22 units**

This analysis helped me understand how product sales volume can vary across different months.

---

# 🧠 Key Learnings

The biggest learning from Day 5 was that data analysis is not only about calculating numbers.

A Data Analyst needs to:

**Understand → Analyze → Question → Interpret → Communicate**

I also learned the importance of distinguishing between:

- Quantity sold vs Revenue
- Number of orders vs Number of customers
- Data-backed findings vs Business hypotheses

For example, when suggesting possible reasons for higher sales, I learned that I should not present assumptions as facts unless the dataset provides evidence.

---

# 📁 Project Structure

```text
Day-05-Retail-Sales-Analysis/
│
├── Day5_Challenge.xlsx
└── README.md
├── Screenshots
    ├── key_findings.png
    ├── data_interpretation.png
    ├── business_question.png
    ├── insight1.png
    ├── insight2.png
    ├── insight3.png
