# 🧹 Data Cleaning Project - Customer Dataset

This project demonstrates practical data cleaning techniques applied to a sample customer dataset using Python (Pandas & NumPy). The dataset contains common data quality issues, and the project focuses on identifying and resolving them to prepare clean, analysis-ready data.

## 📁 Project Structure

* ├── common_data_cleaning_mistakes_dataset.csv # Raw dataset with intentional errors
* ├── Data Cleaning.ipynb # Jupyter Notebook with cleaning process
* ├── Finall Cleaning Data.xls # Final cleaned dataset

## 📊 Dataset Overview

The dataset contains customer information with typical data issues like:

- Missing values in columns: `Name`, `Age`, `Gender`, `Purchase_Amount`, `City`, `Feedback_Score`, `Subscribed`
- Inconsistent category labels (e.g., gender values: `M`, `male`, `F`, `female`)
- Incorrect formats in date fields
- Duplicates and placeholder entries

### Columns:

| Column           | Description             |
|-----------------|--------------------------|
| Customer_ID     | Unique Customer Identifier |
| Name            | Customer Name (may contain missing values) |
| Age             | Customer Age |
| Gender          | Gender of the customer (may need standardization) |
| Purchase_Amount | Amount spent by the customer |
| City            | Customer's city of residence |
| Signup_Date     | Date of Signup |
| Feedback_Score  | Satisfaction score (1 to 5) |
| Subscribed      | Subscription status (Yes/No) |

## 🛠️ Cleaning Techniques Applied

The Jupyter Notebook covers the following steps:

- Handling missing values
- Standardizing categorical columns (`Gender`, `Subscribed`)
- Removing duplicates
- Converting data types (e.g., `Signup_Date` to datetime)
- Outlier detection and removal
- Ensuring consistency across the dataset

## ✅ Final Output

The cleaned dataset is saved as:

`Finall Cleaning Data.xls` — Contains the cleaned, structured dataset ready for further analysis or reporting.

## 💡 Key Learnings

- Importance of careful data inspection before analysis
- Practical Pandas operations for handling real-world messy data
- Common mistakes that can distort analysis if left untreated

## 📦 Requirements

- Python 3.x
- Pandas
- NumPy
- Jupyter Notebook
- xlrd (for Excel reading)

## 🚀 How to Run

1. Clone this repository
2. Install required packages
3. Run `Data Cleaning.ipynb` in Jupyter Notebook
4. Review `Finall Cleaning Data.xls` for cleaned results

---

Feel free to fork, modify, and reuse this project for learning or real-world data preparation tasks!

