# ✈️ British Airways: Predictive Modeling of Customer Bookings
> **Data Science Virtual Experience Project**

![British Airways](https://img.shields.io/badge/British_Airways-Data_Science-blue?style=for-the-badge&logo=british-airways)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

## 📋 Project Overview
This project focuses on predicting customer booking behavior for British Airways. By analyzing historical flight data, I developed a machine learning model to identify high-intent customers and the primary drivers behind successful booking completions.

## 🧠 The Challenge
British Airways receives thousands of booking inquiries daily, but only a fraction convert into finalized tickets. The goal was to:
1. **Explore & Clean** a complex dataset of customer travel patterns.
2. **Train a Random Forest Classifier** to predict booking completion.
3. **Extract Actionable Insights** to help the marketing team target potential travelers more effectively.
   
   (<img width="2951" height="2351" alt="feature_importance" src="https://github.com/user-attachments/assets/52280c7d-bb21-4533-887b-a5653f99bb60" />


## 📊 Key Findings & Results
* **Model Performance:** Achieved an accuracy of 84.23%
* **Top Predictor: Purchase Lead.** The analysis revealed that the "Early Bird" factor is the strongest indicator of booking success—the further in advance a customer searches, the more likely they are to commit.
* **Secondary Drivers:** Flight hour and length of stay were significant contributors to the model's decision-making process.

## 🛠️ Tech Stack
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Machine Learning:** `Scikit-Learn` (Random Forest Classifier)
* **Environment:** `Jupyter Notebook`

## 📂 Repository Structure
* `customer_booking.csv`: The raw dataset used for training and testing.
* `BA_Booking_Prediction.ipynb`: The complete Python workflow from EDA to Model Evaluation.
* `Executive_Summary.pdf`: A professional slide summarizing the findings for stakeholders.

## 🚀 Business Recommendations
1.  **Targeted Retargeting:** Use the high "Purchase Lead" correlation to trigger automated email reminders for customers who search 60+ days out.
2.  **Ancillary Upselling:** Prioritize "Preferred Seat" and "Extra Baggage" offers during high-intent flight hours identified by the model.

---
**Author:** [Edmund Eric GAH]  
**Connect with me:** [https://www.linkedin.com/in/edmund-eric-gah-7432a7213/]
