Heart Disease Analysis
This repository contains an analysis of the heart disease dataset from the UCI Machine Learning Repository. The goal of this project is to identify risk factors associated with heart disease by clustering patients based on their medical history using unsupervised learning techniques.

Dataset
The dataset contains 303 instances with 14 attributes, including:

Age
Sex
Chest pain type
Resting blood pressure
Serum cholesterol
Fasting blood sugar
Resting electrocardiographic results
Maximum heart rate achieved
Exercise-induced angina
ST depression induced by exercise
Slope of the peak exercise ST segment
Number of major vessels colored by fluoroscopy
Thal (Thalassemia)
The target variable indicates the presence (1) or absence (0) of heart disease.

Project Objectives
The main objectives of this project are:

Perform exploratory data analysis (EDA) to gain insights into the dataset.
Preprocess the data by handling missing values, scaling features, and encoding categorical variables.
Apply various clustering algorithms (K-means, Hierarchical, DBSCAN) to group patients into clusters based on their medical history.
Visualize the clusters using Principal Component Analysis (PCA) and t-SNE.
Use Gaussian Mixture Models (GMMs) to identify risk factors associated with heart disease.
Evaluate the performance of the clustering algorithms using metrics like Silhouette Score and Davies-Bouldin Index.
Compare the performance of different clustering algorithms and determine the best one.

Repository Structure

heart-disease-analysis/
│
├── heart_disease_analysis.ipynb # Jupyter notebook containing the analysis
├── heart.csv # Dataset used in the project
├── README.md # This README file

How to Run

1. Clone this repository:  
   git clone https://github.com/RuthBiney/Heart-Disease-Analysis.git

2. Install the required Python packages:
   pip install -r requirements.txt

3. Run the Jupyter notebook:
   jupyter notebook Heart_Disease_Dataset_Analysis.ipynb
