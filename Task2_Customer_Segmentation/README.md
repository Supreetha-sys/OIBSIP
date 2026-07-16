# Customer Segmentation using K-Means Clustering

## Project Overview
This project focuses on **Customer Segmentation** using the Mall Customers dataset. The objective is to group customers into different segments based on their **Annual Income** and **Spending Score** using the **K-Means Clustering** algorithm. These customer segments help businesses understand customer behavior and create targeted marketing strategies.

## Objective
- Analyze customer data.
- Perform Exploratory Data Analysis (EDA).
- Identify the optimal number of clusters using the Elbow Method.
- Apply the K-Means Clustering algorithm.
- Visualize customer segments.
- Understand customer purchasing behavior.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn


## Dataset
**Dataset:** Mall Customers Dataset (.csv)

The dataset contains customer information such as:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)


## Exploratory Data Analysis (EDA)
The following analyses were performed before applying the clustering algorithm:

- Imported the required Python libraries.
- Loaded the dataset.
- Explored dataset shape and information.
- Checked for missing values.
- Generated descriptive statistics.
- Visualized Gender Distribution.
- Visualized Age Distribution.
- Visualized Annual Income Distribution.
- Visualized Spending Score Distribution.
- Created a Scatter Plot of Annual Income vs Spending Score.


## Machine Learning Steps Performed
- Selected Annual Income and Spending Score as features.
- Applied the Elbow Method to determine the optimal number of clusters.
- Identified **K = 5** as the optimal number of clusters.
- Applied the K-Means Clustering algorithm.
- Assigned cluster labels to each customer.
- Visualized customer segments using a scatter plot.
- Saved the clustered dataset as a new CSV file.


## Cluster Summary

| Cluster Analysis | Description |
|------------------|-------------|
| Cluster 1 | Customers with similar spending behavior |
| Cluster 2 | High Income - High Spending customers |
| Cluster 3 | Low Income - High Spending customers |
| Cluster 4 | High Income - Low Spending customers |
| Cluster 5 | Low Income - Low Spending customers |

---

## Project Structure

```
Task2_Customer_Segmentation/
│── Mall_Customers.csv
│── Customer_Segments.csv
│── Supreetha_Task2.ipynb
│── README.md
```

## How to Run the Project

1. Clone the repository.
2. Open the project in Jupyter Notebook.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn
```

4. Run all cells in the notebook.


## Results
- Successfully analyzed customer data.
- Determined the optimal number of clusters using the Elbow Method.
- Segmented customers into **5 distinct groups**.
- Visualized customer groups using K-Means Clustering.
- Generated a new dataset named **Customer_Segments.csv** containing cluster labels for each customer.


## Learning Outcomes
Through this project, I learned how to:
- Perform Exploratory Data Analysis (EDA).
- Visualize customer data using different charts.
- Understand the concept of Customer Segmentation.
- Apply the K-Means Clustering algorithm.
- Use the Elbow Method to determine the optimal number of clusters.
- Visualize machine learning results.
- Save and analyze clustered datasets.


##  Conclusion
Customer segmentation was successfully performed using the K-Means Clustering algorithm. The Elbow Method identified **5** as the optimal number of clusters. Customers were grouped based on their **Annual Income** and **Spending Score**, providing valuable insights that can help businesses improve marketing strategies and customer engagement.


## Author

**Supreetha**  
Aspiring Data Analyst
