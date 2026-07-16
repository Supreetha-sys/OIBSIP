#  Data Cleaning using Python

## Project Overview
This project focuses on **Data Cleaning** using the Titanic dataset. The primary objective is to identify and handle missing values, remove unnecessary columns, check for duplicate records, and prepare the dataset for further analysis or machine learning.


## Objective
- Clean the Titanic dataset.
- Handle missing values appropriately.
- Remove unnecessary columns.
- Check for duplicate records.
- Prepare the dataset for analysis and predictive modeling.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy


## Dataset
**Dataset:** Titanic Dataset (.csv)

The dataset contains passenger information such as:
- Passenger ID
- Survival Status
- Passenger Class
- Name
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket Number
- Fare
- Cabin
- Embarkation Port


## Data Cleaning Steps Performed
- Imported the required Python libraries.
- Loaded the Titanic dataset.
- Explored the dataset structure.
- Checked dataset shape and information.
- Identified missing values.
- Filled missing values in the **Age** column using the **Median**.
- Filled missing values in the **Embarked** column using the **Mode**.
- Removed the **Cabin** column due to a large number of missing values.
- Checked for duplicate records.
- Saved the cleaned dataset as a new CSV file.


## Data Cleaning Summary

| Column | Action Performed |
|---------|------------------|
| Age | Missing values filled using Median |
| Embarked | Missing values filled using Mode |
| Cabin | Removed due to excessive missing values |
| Duplicate Rows | Checked (No duplicates found) |


## Project Structure

```
Task3_Data_Cleaning/
│── Titanic-Dataset.csv
│── Cleaned_Titanic_Dataset.csv
│── Supreetha_Task3_Data_Cleaning.ipynb
│── README.md
```


## How to Run the Project

1. Clone the repository.
2. Open the project in Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy
```

4. Run all cells in the notebook.


## Results
- Successfully handled missing values.
- Removed an unnecessary column with excessive missing data.
- Verified that no duplicate records exist.
- Generated a cleaned dataset named **Cleaned_Titanic_Dataset.csv**.
- Prepared the dataset for further analysis and machine learning tasks.


## Learning Outcomes
Through this project, I learned how to:
- Load and inspect datasets using Pandas.
- Identify missing values.
- Handle missing values using Median and Mode.
- Remove unnecessary columns.
- Check for duplicate records.
- Save a cleaned dataset.
- Apply real-world data cleaning techniques used by Data Analysts.


## Conclusion
The Titanic dataset was successfully cleaned by handling missing values, removing unnecessary columns, checking for duplicate records, and saving the cleaned dataset. The cleaned dataset is now suitable for Exploratory Data Analysis (EDA), visualization, and machine learning applications.


## Author

**Supreetha**  
Aspiring Data Analyst
