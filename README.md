# Data Science Project 1 - Titanic Survival Analysis 🛳️

## 📌 Overview
This project explores the **Titanic dataset**, analyzing survival trends based on **gender, passenger class, and age groups**. It includes **data visualization, feature engineering, and analysis**.

## 📂 Project Features
✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Feature Engineering (`AgeClass` creation)  
✔ Data Visualization with Matplotlib & Pandas  
✔ Assignments & Exercises  

## 📊 Visualizations
- Bar charts showing survival trends by **Sex & Class**
- Grouped bar charts for **Survival by AgeClass**
  
## 🚀 Technologies Used
- Python 🐍
- Pandas 📊
- Matplotlib 📈

# Project 2: Dataset Merging, Data Manipulation, and K-Means Clustering

This project involves merging two datasets, performing data manipulation, and applying the K-Means clustering algorithm to analyze student performance based on term test results.

---

## **Project Overview**
The goal of this project is to:
1. Merge two datasets containing student term test results.
2. Perform data manipulation to calculate the best marks and average marks for each student.
3. Apply the K-Means clustering algorithm to group students based on their average marks.
4. Visualize the clusters to analyze student performance.

---

## **Files in the Repository**
- `term-test-1-result.csv`: Contains Term Test 1 results for 50 students.
- `term-test-2-result.csv`: Contains Term Test 2 results for 50 students.
- `final-term-test-result.csv`: The merged and processed dataset with best marks and average marks.
- `project2.py`: The Python script for data manipulation, merging, and clustering.
- `README.md`: This file, providing an overview of the project.

---

## **Steps Performed**
1. **Dataset Creation**:
   - Two CSV files (`term-test-1-result.csv` and `term-test-2-result.csv`) were created with 50 students' data, including their registration numbers, names, and term test marks.

2. **Data Merging**:
   - The two datasets were merged on the `Registration Number` column using pandas.

3. **Data Manipulation**:
   - A new column, `Best Marks`, was added to store the highest marks between the two term tests for each student.
   - A new column, `Average Marks`, was added to store the average marks of the two term tests for each student.
   - The `TT-1 Marks` and `TT-2 Marks` columns were dropped from the final dataset.

4. **Save Processed Data**:
   - The processed dataset was saved as `final-term-test-result.csv`.

5. **K-Means Clustering**:
   - The K-Means clustering algorithm was applied to the `Average Marks` column to group students into clusters.
   - The optimal number of clusters was determined using the **Elbow Method**.
   - The clusters were visualized using a scatter plot.

---

## **How to Run the Code**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/project2-dataset-merging-kmeans.git

## 📄 Assignment Details
This repository also includes an **assignment** where students analyze survival trends and answer key questions.

---

🔗 **Live Notebook:** (https://colab.research.google.com/drive/1FXf9riXPITCk_pXkrYScKmuYiqjSbvO9?usp=sharing)
📂 **Dataset:** [Titanic Dataset (Kaggle)]  
📌 **Created By:** Md Shoriful Alam
