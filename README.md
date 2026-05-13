# Bike Buyer Behavior Analysis — Excel Dashboard Project

## Project Overview
This is an end-to-end data analysis project built entirely in 
Microsoft Excel. The project explores the purchasing behavior 
of 1,000 bike shop customers by analyzing their demographics, 
income levels, commute distances and lifestyle factors to 
understand what drives a customer to purchase a bike or not.

---

## Dashboard Preview
![Dashboard Preview](dashboard/dashboard_preview.png)

---

## Tools Used
- Microsoft Excel
  - Data Cleaning and Preparation
  - Pivot Tables
  - Nested IF Formulas
  - Charts and Visualizations
  - Slicers (Interactive Filters)
  - Dashboard Design

---

## Project Structure
- **data/** — Original raw dataset of 1,000 bike shop customers
- **analysis/** — Working sheet with cleaned data and pivot tables
- **dashboard/** — Final interactive Excel dashboard
- **insights/** — Key insights PDF report

---

## Dataset Overview
The dataset contains demographic and lifestyle information 
on 1,000 bike shop customers including:

- Marital Status
- Gender
- Annual Income
- Number of Children
- Education Level
- Occupation
- Home Ownership
- Number of Cars
- Daily Commute Distance
- Region
- Age
- Whether they purchased a bike or not

---

## Data Cleaning Steps
The following cleaning steps were performed on the raw dataset:

1. Removed duplicate rows to ensure each customer appears once
2. Expanded abbreviations using Find and Replace:
   - M → Married, S → Single
   - M → Male, F → Female
3. Formatted income column to currency
4. Created Age Brackets column using nested IF formula:
   - Under 18 → Teenager
   - 18 to 30 → Young Adult
   - 31 to 64 → Middle Aged
   - 65 and above → Senior

---

## Dashboard Features
The interactive dashboard includes:

- **Bar Chart** — Average income by gender comparing 
  buyers vs non buyers
- **Clustered Bar Chart** — Bike purchase decision 
  broken down by age group
- **Line Chart** — Bike purchase trends across 
  different commute distances
- **Interactive Slicers** — Filter all charts 
  simultaneously by:
  - Marital Status
  - Region
  - Education Level

---

## Key Insights

### 1. Income Drives Bike Purchase Decisions
Customers who purchased a bike had a consistently higher 
average income. Male buyers averaged approximately $60,000 
while female buyers averaged around $55,000. This suggests 
pricing and marketing should target middle to higher 
income brackets.

### 2. Middle Aged Customers Are the Core Buyer Segment
831 out of 1,000 customers (83.1%) were Middle Aged (31–54). 
This is the only age group where purchases (425) outnumbered 
non purchases (406), giving a conversion rate of 51.1%. 
Young Adults had only 35.4% and Seniors just 28.8%.

### 3. Shorter Commutes Drive Higher Purchase Rates
Customers living 0–1 miles from work had the highest 
purchase rate at 54.6% (200 out of 366). Those commuting 
10+ miles had the lowest rate at just 29.7% (33 out of 111). 
Most buyers use bikes for short distance commuting.

### 4. Income Is a Stronger Predictor Than Gender
A consistent income gap exists between male and female 
customers across all categories. Despite earning less 
on average female customers still showed strong purchase 
intent, confirming that income level is a more reliable 
predictor of bike purchase behavior than gender alone.

---

## Ideal Buyer Profile
Based on the analysis the most likely bike buyer is:

| Factor | Profile |
|--------|---------|
| Age | 31 to 54 years old (Middle Aged) |
| Income | $55,000 or above |
| Commute | Lives within 0–2 miles from workplace |
| Gender | Both male and female show strong intent |

---

## Skills Demonstrated
- Data cleaning and preparation
- Pivot table creation and management
- Dashboard design and professional formatting
- Business insight generation
- Data storytelling and communication

---

## Author
**Your Name**
Aspiring Data Analyst
[LinkedIn](your linkedin url here) | [GitHub](your github url here)