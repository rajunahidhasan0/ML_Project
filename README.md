# **Project Title**: ML Project: Human Activity Recognition

## **Project Overview**
This repository showcases a comprehensive machine learning project focused on solving activity recognition. The project involved data preprocessing, feature engineering, and the application of 10 different classification models to evaluate their performance.

The primary objective was to determine which model provides the best accuracy for the given dataset and to compare the performance of these models. The classification models used include:

1. **Logistic Regression**
2. **Decision Tree**
3. **Random Forest**
4. **Gaussian Naive Bayes**
5. **Support Vector Machine (SVM)**
6. **K-Nearest Neighbors (KNN)**
7. **AdaBoost**
8. **Gradient Boosting**
9. **XGBoost**
10. **Artificial Neural Network (ANN)**

Each model's performance was evaluated using metrics like accuracy, precision, recall, and F1-score to ensure a robust comparison. This project demonstrates the process of exploring and comparing machine learning techniques to achieve the best results.

---

## **Project Structure**
- **`src/`**: Contains all scripts used for data preprocessing and modeling.
- **`data/`**: Holds processed datasets used for training and evaluation.
- **`notebooks/`**: Includes Jupyter notebooks detailing the implementation and results.
- **`README.md`**: Project documentation.

---

## **Key Features**
1. **Data Extraction**: Automatically extracts and organizes data from a compressed file (`DataSet.zip`).
2. **Data Parsing**: Utilizes Python libraries like `glob` to parse and structure data into DataFrames for further processing.
3. **Preprocessing**:
   - Identifies and handles missing values.
   - Normalizes and scales data for efficient modeling.
   - Implements exploratory data analysis using `matplotlib` and `seaborn` to visualize trends and insights.

---

## **Technologies Used**
- **Languages**: Python
- **Libraries**:
  - **Data Processing**: Pandas, NumPy
  - **Visualization**: Matplotlib, Seaborn
  - **Utilities**: Glob, ZipFile
- **Tools**:
  - Jupyter Notebook
  - Git for version control

---

## **Getting Started**
1. Clone this repository:
   ```bash
   git clone https://github.com/rajunahidhasan0/ML_Project.git
