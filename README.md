# NLP-Based Job Market Analysis and Prediction Model

This repository presents the **NLP-Based Job Market Analysis and Prediction Model**, a comprehensive project developed to analyze the job market for data-related roles (Data Scientists, Data Engineers, and Data Analysts) and predict important job attributes, including salary ranges and top hiring industries. This project was completed as part of the course **IE7275 - Data Management for Analytics** in Spring 2023.

---

## Overview

The project aims to solve the issue of unreported salaries in job postings and provide valuable insights into hiring trends, skills in demand, and job market dynamics. Using advanced Natural Language Processing (NLP) techniques and machine learning, we built predictive models with a strong emphasis on feature refinement and model optimization.

### Key Features:
- Predicted salary ranges with **91.84% accuracy** using a **Gradient Boosting Classifier**.
- Extracted insights from job descriptions using NLP techniques such as **tokenization** and **TF-IDF**.
- Improved model performance through **hyperparameter tuning** with grid search and cross-validation across three models: K-Nearest Neighbors (KNN), Random Forest Regression (RFR), and AdaBoost.
- Highlighted top hiring industries and trends in the job market using data visualization and analysis.

---

## Repository Content

This repository contains:
1. **Final_Coding_File.ipynb**: Python notebook showcasing data preprocessing, feature engineering, and model implementation.
2. **DM_Project_Data_Cleaning.ipynb**: Notebook detailing the data cleaning and preprocessing steps.
3. **Final_Project_Report.pdf**: Comprehensive report on the project methodology, results, and insights.
4. **Data_Collection_Visualization_Processing.pdf**: Documentation on data collection, visualization, and processing.
5. **Model_Performance_Evaluation.pdf**: Evaluation and interpretation of model performance.
6. **Exploration_of_Candidate_Models.pdf**: Exploration and selection of candidate models for the prediction task.
7. **Final_Project_Proposal.pdf**: Initial proposal outlining project objectives and milestones.

---

## Problem Statement

The job market for data professionals often lacks transparency, with many job postings missing key details such as salary ranges. This project addresses these challenges by:
1. Predicting salary ranges for job postings using job descriptions as input.
2. Identifying top industries, locations, and skills in demand for data-related roles.
3. Analyzing job descriptions to extract actionable insights for companies and candidates.

### Objectives:
- Predict salary ranges and hiring industries with high accuracy.
- Identify the most in-demand skills and qualifications for data professionals.
- Explore job descriptions to uncover patterns in required skills, job titles, and regions.

---

## Data and Methods

### Data Sources
The datasets for this project were sourced from Kaggle:
1. [Data Analyst Jobs](https://www.kaggle.com/datasets/durgeshrao9993/data-analyst-jobs-datset)
2. [Data Scientist Jobs](https://www.kaggle.com/datasets/andrewmvd/data-scientist-jobs)
3. [Data Engineer Jobs](https://www.kaggle.com/datasets/andrewmvd/data-engineer-jobs)

### Data Overview
- **8676 rows** and **16 columns** after merging datasets.
- Key attributes: Job Title, Salary Estimate, Job Description, Company Name, Location, Industry, Sector, and Revenue.

### Techniques Used
1. **Data Cleaning and Feature Engineering**:
   - Null value handling and column removal (e.g., "Easy Apply," "Competitors").
   - One-hot encoding for categorical variables.
   - Label encoding for ordinal features.
2. **NLP Techniques**:
   - **Tokenization** and **TF-IDF** to extract and analyze job description features.
   - Frequency analysis of 200 skills reduced to six final features: ['Python', 'SQL', 'Excel', 'Machine Learning', 'Spark', 'AWS'].
3. **Modeling**:
   - Gradient Boosting Classifier (final model with 91.84% accuracy).
   - Comparison with K-Nearest Neighbors (KNN), Random Forest Regression (RFR), and AdaBoost.
4. **Model Optimization**:
   - Grid search for hyperparameter tuning.
   - Cross-validation for robust performance evaluation.

---

## Results and Insights

### Key Insights:
1. **Top Hiring Locations**:
   - Major hubs: **New York, Chicago, San Francisco**.
   - States with high demand: **California, Illinois, Texas**.
2. **Salary Predictions**:
   - Salary ranges predicted with 91.84% accuracy.
   - Clear patterns observed between job roles and salary brackets.
3. **Top Skills in Demand**:
   - Programming: **Python, SQL, Excel**.
   - Tools: **Machine Learning, Spark, AWS**.
4. **Top Industries**:
   - Technology, Finance, and Healthcare.

### Visualizations:
- Distribution of salaries across job titles and locations.
- Box plots for starting and ending salaries.
- Word frequency analysis of job descriptions to highlight in-demand skills.

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/nlp-job-market-analysis.git
   ```
2. Install required dependencies using `requirements.txt`.
3. Explore the notebooks for data cleaning, visualization, and modeling.
4. Refer to the project report PDFs for detailed explanations and results.

---

## Applications

1. **For Job Seekers**:
   - Estimate salary ranges for desired job titles and industries.
   - Identify key skills to enhance their profiles.
2. **For Companies**:
   - Benchmark salaries for new hires.
   - Optimize hiring strategies based on market trends.

---

## Acknowledgments

This project was completed under the guidance of **Professor Dr. Venkat Krishnamurthy** at Northeastern University. Contributors:
- **Valli Meenaa Vellaiyan**
- **Hrithik Sarda**

Special thanks to Kaggle for providing the datasets.

---

## License

This project is licensed under the **MIT License**.
