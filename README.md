# Cyber Attack Classification Analysis and Feature Engineering

## 🏗️ Project Context
This project was developed during the third term of the Post-Degree Diploma in Data Analytics at Langara College. It was inspired by the academic research *“Evaluating the Impact of Filter-Based Feature Selection in Intrusion Detection Systems”* ([link](https://link.springer.com/article/10.1007/s10207-023-00767-y)), and aimed to combine a rigorous exploratory analysis with advanced feature selection and machine learning techniques.

## 📌 Project Overview

The project focuses on analyzing a large-scale network traffic dataset (BCCC-CIC IDS 2017) to distinguish benign traffic from multiple types of cyber-attacks. Through a combination of exploratory data analysis, feature selection, and supervised modeling, the study explores the extent to which feature engineering can reduce redundancy, improve interpretability, and enhance predictive performance in intrusion detection systems.

## 🎯 Objective

- Explore different feature selection techniques (Chi-Square, ANOVA, Mutual Information, Random Forest importance) to identify the most relevant attributes for distinguishing benign traffic from cyber-attacks.  
- Perform exploratory data analysis (EDA) to uncover distributions, correlations, and outlier patterns between benign and attack traffic across key feature groups.  
- Build and evaluate machine learning models, with emphasis on Random Forest, to classify cyber-attacks and assess predictive performance using selected features.  

## 🛠 Tools & Technologies

- **Language & Libraries:** Python (pandas, numpy, matplotlib, seaborn, scikit-learn)  
- **Feature Selection:** Chi-Square, ANOVA, Mutual Information, Random Forest importance  
- **Modeling:** Random Forest classifier  
- **Environment:** Jupyter Notebook (VS Code)  

## 📊 Key Steps

1. **Data Preparation & Exploration**  
   - Loaded over 2.4M rows and 122 features from the BCCC-CIC IDS 2017 dataset.  
   - Conducted exploratory data analysis (EDA) to compare benign vs. attack traffic patterns.  

2. **Feature Selection & Engineering**  
   - Applied multiple filter-based feature selection methods to reduce redundancy.  
   - Identified the most predictive features while simplifying model complexity.  

3. **Model Development & Evaluation**  
   - Built and trained Random Forest classifiers.  
   - Compared full models with reduced feature sets to assess trade-offs in accuracy vs. interpretability.  

## 🚀 Results

- The final Random Forest model using **36 selected predictors** achieved an accuracy of **99.943%**.  
- Feature selection significantly reduced dataset complexity while retaining strong predictive performance.  
- Exploratory data analysis revealed clear contrasts in distribution, correlation, and outlier behavior between benign and attack traffic.  
- The study demonstrates how combining feature engineering with robust machine learning can deliver highly effective intrusion detection systems.  

## 📂 Repository Structure

```
├── Data/              # See Text File
├── Src/           # Jupiter Notebook scripts for analysis and modelling
├── Documentation/   # Final project report
└── README.md          # Project description
```