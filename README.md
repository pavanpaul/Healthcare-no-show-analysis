# Healthcare Appointment No-Show Analysis

Missed medical appointments are a challenge that many healthcare systems face. These missed visits can disrupt clinic operations, lead to underutilized resources, and potentially affect patient outcomes due to delayed treatment. This project takes a deep dive into analyzing and understanding the patterns and behaviors that contribute to no-shows.

## Project Purpose

The aim of this project is to explore, analyze, and predict why patients miss their scheduled medical appointments. The insights gained here can help healthcare providers take proactive steps to reduce no-show rates and improve the efficiency of appointment scheduling systems.

---

## Tools Used

* Python (for data preprocessing and feature engineering)
* SQL (for exploratory data analysis)
* Power BI (for interactive reporting and dashboards)
* Machine Learning (Random Forest, SMOTE for class imbalance handling)
* GitHub (for version control and sharing the project)

---

## Project Files

* **HealthCare\_Appointment\_Project.ipynb** – Initial data cleaning, transformation, and feature creation.
* **EDA(HealthCare) in SQL.ipynb** – Exploratory data analysis performed using SQL queries.
* **PREDICTIVE MODELLING(HealthCare).ipynb** – Training and evaluation of the Random Forest classifier.
* **Healthcare Visualization.pbix** – A visually interactive dashboard created in Power BI.

---

## Main Objectives

1. Understand what influences patient no-shows**: We investigated age, gender, SMS reminders, and waiting times.
2. Analyze the effectiveness of SMS communication**: We tested if receiving an SMS impacts the show-up rate.
3. Study scheduling behavior**: We looked at patterns around days of the week and how long patients wait.
4. Predict no-show behavior**: We built a machine learning model that predicts the likelihood of a no-show.
5. Recommend improvements**: Based on our insights, we suggest practical steps to reduce no-shows.

---

## Key Insights

* **SMS Reminders Work**: Patients who received SMS reminders were more likely to attend.
* **Younger Patients Miss More**: The no-show rate was highest among patients under 30.
* **Long Wait = High No-Show**: As the waiting days between scheduling and the actual appointment increased, so did the chance of a no-show.
* **Weekdays Matter**: Most no-shows occurred on Mondays and Tuesdays.

---

## Machine Learning Model

I used the **Random Forest Classifier** to predict whether a patient would show up. Since our data had more "show-ups" than "no-shows," we used **SMOTE** to balance it. The model reached an accuracy of around **78%**.

### Why Random Forest?

* It’s easy to interpret.
* It handles imbalanced data well.
* It provides feature importance to understand what matters most.

### Key Features:

* SMS Received
* Waiting Days
* Age
* IsWeekend (derived feature)

---

## Power BI Dashboard Highlights

* **KPIs**: Total Appointments, No-Show Rate, SMS Effectiveness
* **Visuals**:

  * Bar Charts showing medical condition vs show-up
  * Line Graph for Waiting Days trend
  * Pie Charts for Age and Gender breakdown
  * Column Chart comparing show vs no-show across weekdays

---

## Final Thoughts

This project was not just about analyzing data – it was about turning that data into meaningful stories. By combining programming, querying, visualization, and modeling, we’ve built a complete narrative that can guide decisions in the healthcare space.

---

## Author 

PAVAN PAUL 

EMAIL:pavanpaul0806@gmail.com

