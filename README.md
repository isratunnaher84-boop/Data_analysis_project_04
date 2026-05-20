# Data_analysis_project_04
# Customer Shopping Behaviour Analysis

## Overview

This project focuses on analyzing customer shopping behaviour using Python, SQL, and Power BI. The analysis was conducted on transactional customer purchase data to uncover insights related to spending patterns, customer segmentation, subscription behaviour, product performance, and purchasing trends.

The workflow includes:

* Data loading and cleaning in Python
* Exploratory Data Analysis (EDA)
* SQL-based business analysis
* Dashboard creation in Power BI
* Presentation of findings using Gamma

The project demonstrates an end-to-end data analytics workflow commonly used in real-world business analysis.

---

## Dataset

The dataset contains customer transaction records from multiple product categories.

### Dataset Information

* **Rows:** 3,900
* **Columns:** 18

### Key Features

* Customer demographics

  * Age
  * Gender
  * Location
  * Subscription Status

* Purchase details

  * Item Purchased
  * Category
  * Purchase Amount
  * Season
  * Size
  * Color

* Shopping behaviour

  * Discount Applied
  * Previous Purchases
  * Review Rating
  * Shipping Type
  * Frequency of Purchases

### Data Quality

* Missing values were found in the `Review Rating` column
* Data inconsistencies and redundant columns were cleaned during preprocessing

---

## Tools & Technologies

### Programming & Analysis

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn

### Database

* **MySQL**

### Visualization

* **Power BI**

### Reporting

* **Gamma**

### Development Environment

* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Imported dataset using Pandas
* Explored dataset structure using:

  * `df.info()`
  * `df.describe()`

### 2. Data Cleaning

* Handled missing values
* Imputed missing review ratings using median ratings by product category
* Renamed columns into snake_case format
* Removed redundant columns
* Checked for consistency in categorical variables

### 3. Feature Engineering

Created new features such as:

* `age_group`
* Customer purchase frequency metrics

### 4. Exploratory Data Analysis (EDA)

Performed analysis to identify:

* Customer spending patterns
* Product popularity
* Revenue trends
* Subscription behaviour
* Purchase frequency insights

### 5. SQL Analysis

Executed SQL queries to answer business-related questions including:

* Revenue by gender
* High-spending discount users
* Top-rated products
* Shipping type comparison
* Subscriber vs non-subscriber revenue analysis
* Customer segmentation
* Revenue contribution by age group

### 6. Dashboard Creation

Built an interactive Power BI dashboard to visualize:

* Revenue trends
* Customer segments
* Product performance
* Subscription insights
* Purchase behaviour patterns

### 7. Presentation

Created a professional presentation using Gamma to summarize:

* Key findings
* Business insights
* Recommendations
* Dashboard highlights

---

## Dashboard

The Power BI dashboard includes:

* Revenue analysis
* Customer segmentation visuals
* Product performance tracking
* Subscription behaviour analysis
* Shipping and discount insights

---

## Key Results

### Major Insights

* Subscribers contributed significantly higher revenue than non-subscribers
* Certain products showed strong dependency on discounts
* Loyal customers generated consistent repeat purchases
* Specific age groups contributed the highest revenue
* Top-rated products also showed strong purchase frequency

### Business Recommendations

* Improve subscription-based marketing strategies
* Introduce stronger loyalty programs
* Optimize discount strategies for profitability
* Promote top-rated products in campaigns
* Target high-value customer segments with personalized offers

### 4. Run the Analysis

* Open the notebook file
* Run cells sequentially
* Connect MySQL database if required
* Load Power BI dashboard file for visualization

---
## Project Structure

```bash
├── dataset/
├── notebooks/
├── sql_queries/
├── dashboard/
├── presentation/
├── visuals/
├── README.md
```

---

## Conclusion

This project demonstrates practical skills in:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* SQL querying and business analysis
* Data visualization
* Dashboard development
* Business insight reporting

The project reflects a complete analytics workflow from raw data to business recommendations and visualization.

---

## Author

**[Isratun Naher]**
Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization
