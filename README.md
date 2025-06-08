# Healthcare Appointment No-Show Analysis

## Project Overview

This project analyzes patient appointment data to predict no-shows and uncover factors influencing appointment attendance. By leveraging data preprocessing, exploratory data analysis (EDA), and predictive modeling, the goal is to help healthcare providers reduce missed visits and improve operational efficiency.

## Dataset

The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments) and contains anonymized patient appointment records, including demographic details, medical history, appointment dates, and attendance status.

## Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)  
- SQL (for data exploration and analysis)  
- SMOTE (to handle class imbalance)  
- Power BI (for interactive data visualization)  
- Google Colab (for cloud-based coding and analysis)

## Project Workflow

1. **Data Collection & Import**  
   - Downloaded dataset from Kaggle and imported it into Google Colab for processing.

2. **Data Preprocessing**  
   - Cleaned missing values and engineered features such as waiting days (time between scheduling and appointment) and SMS reminder flags.

3. **Exploratory Data Analysis (EDA)**  
   - Used SQL queries to identify trends and patterns in no-shows based on demographics, medical conditions, and neighborhoods.

4. **Predictive Modeling**  
   - Built classification models using Logistic Regression and Random Forest algorithms.  
   - Applied SMOTE to address class imbalance and improve model accuracy.

5. **Data Visualization**  
   - Developed an interactive Power BI dashboard to highlight key insights and support strategic decision-making.

## Key Findings

- Younger patients and certain neighborhoods showed higher no-show rates.  
- SMS reminders and shorter waiting times positively impacted attendance.  
- The Random Forest model with SMOTE yielded improved prediction performance compared to baseline models.

## How to Run

- Open the Jupyter notebooks in the `/notebooks` directory using Google Colab or Jupyter locally.  
- Follow the step-by-step analysis from data preprocessing to modeling and visualization.  
- Power BI dashboard files are located in `/visualizations`. (Instructions for accessing or viewing the dashboard can be added here.)

## Final Thoughts

This project demonstrates the power of combining data analysis and predictive modeling to address real-world healthcare challenges. By identifying patterns in patient no-shows, healthcare providers can take proactive measures such as targeted reminders and optimized scheduling to improve appointment adherence. The insights and tools developed here have the potential to enhance patient care while increasing operational efficiency.


## Author 

PAVAN PAUL 

EMAIL:pavanpaul0806@gmail.com

