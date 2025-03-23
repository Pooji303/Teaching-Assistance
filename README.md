# Teaching-Assistance-PRCP1026

## Project Overview
The *PRCP-1026 Teaching Assistance* project focuses on analyzing teaching performance and building predictive models to assess student performance based on given factors. The dataset contains teaching evaluations over multiple semesters at the Statistics Department of the University of Wisconsin-Madison.

## Problem Statement
### Task 1: Data Analysis Report
- Perform a complete data analysis on the given dataset.
- Identify trends, patterns, and insights using statistical and visualization techniques.

### Task 2: Predictive Model for Student Performance
- Build a machine learning model to predict student performance (Low, Medium, High).
- Evaluate multiple models and suggest the best one for production use.

### Task 3: Model Comparison Report
- Compare the performance of different models based on evaluation metrics.
- Recommend the most accurate and efficient model for deployment.

### Task 4: Challenges Faced & Solutions
- Document challenges encountered in data preprocessing, feature engineering, and model training.
- Provide explanations of techniques used to resolve these challenges.

---

## Dataset Information
The dataset consists of evaluations of teaching assistants (TAs) and includes:
- **Native_teacher**: Whether the TA is a native English speaker (1=Yes, 2=No)
- **Instructor**: Course instructor identifier (25 categories)
- **Course**: Course identifier (26 categories)
- **Semester**: Summer (1) or Regular (2)
- **Class_size**: Number of students in the class
- **Class_attribute**: Teaching performance rating (1=Low, 2=Medium, 3=High)

### Dataset Link:
📥 *[Download Dataset](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/PRCP-1026-TeachingAssistance.zip)*

---

## Repository Structure
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for analysis
├── src/ # Scripts for preprocessing and modeling
├── references/ # Documentation and resources
└── README.md # Project documentation

---

## Technologies Used
- *Programming Language*: Python  
- *Libraries*: Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
