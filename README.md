# arthur.github.io

Week 0 setup completed by Arthur Nwashindi

## Week 1 – Foundations of Data Analytics

In this week, I learned:
•The difference between data and information
•What data analytics is
•Key data roles and workflows

# 📊 R Programming Portfolio – Housing Data Analysis

This project demonstrates data analysis using R, focusing on UK housing and income data.

---

## 🧰 Tools & Libraries

* R
* dplyr
* ggplot2
* readr
* RStudio

---

## 📁 Project Overview

This analysis explores housing data, including income, employment status, and property types across regions in the UK.

---

## 🔹 Step 1: Load Required Libraries

```r
library(dplyr)
library(ggplot2)
library(readr)
```

![Load Libraries](screenshots/load_libraries.png)

---

## 🔹 Step 2: Import Dataset

```r
housing_data <- read_csv("datasets/uk_housing_income_dataset.csv")
```

![Import Dataset](screenshots/import_dataset.png)

---

## 🔹 Step 3: View First Rows

```r
head(housing_data)
```

![View Data](screenshots/view_data.png)

---

## 📊 Key Insights

* Dataset contains **650 observations and 10 variables**
* Includes demographic and financial variables such as:

  * Age
  * Income
  * Housing Cost
  * Employment Status
* Data is ready for further analysis and visualization

---

## 📌 Skills Demonstrated

* Data Importing in R
* Data Inspection
* Use of tidyverse libraries
* Project structuring in RStudio

---

## 📂 Folder Structure

```
Week12_Housing_Analysis/
│
├── datasets/
├── outputs/
├── screenshots/
├── scripts/
├── README.md
```

---

## 👤 Author

Arthur Nwashindi
(Data Analytics Portfolio)
