# **📊 Bank Telephonic Marketing: Subscription Prediction**

## **🔗 Overview**
Predict customer subscription to term deposits using telephonic marketing data. This project leverages machine learning and data visualization to improve campaign targeting.

---

## **🛠 Tech Stack**

| ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)  ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  ![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)  ![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=black)  ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F61?style=for-the-badge&logo=appveyor&logoColor=white) |

---

## **🔄 Workflow**

![Workflow Diagram](images/workflow.png)  
*The process begins with dataset preprocessing, followed by model training and evaluation. The results are then visualized using Power BI and deployed through a Streamlit app.*

1. **Data Preprocessing**:  
   - Clean and transform the data for model training.
   - detecting and removing Outliers
   - Address class imbalance using SMOTE.

2. **Model Training**:  
   - Train machine learning models including Logistic Regression, Random Forest, and optimized Random Forest with hyperparameter tuning.  
   - Implement cross-validation and hyperparameter optimization using GridSearchCV.

3. **Model Evaluation**:  
   - Evaluate models using Accuracy, F1 Score, and Confusion Matrix.  
   - Select the best-performing model.

4. **Visualization**:  
   - Generate key insights using Power BI.  
   - Use a Streamlit app for real-time predictions and insights.

5. **Deployment**:  
   - Submit predictions in CSV format for leaderboard ranking.

---

![Power BI Dashboard](https://github.com/akashBhaiya/5995/blob/main/Screenshot%202025-01-19%20023941.png)  
*Above: Power BI Dashboard showcasing front page and theme.*

---

## **📈 Key Insights**
- **Subscription Rates**: ~3.5% of customers subscribe.
- **Call Duration**: Longer calls correlate with higher subscriptions.
- **Age & Job Type**: Critical factors influencing subscriptions.

![Customer Insights](https://github.com/akashBhaiya/5995/blob/main/Screenshot%202025-01-19%20024040.png)  
*Demographics and behavior trends impacting outcomes.*

---

## **🗂 Dataset**
- **Train**: 40,000 rows, 17 columns.
- **Test**: 5,211 rows, 16 columns.
- **Target**: `y` (yes/no subscription).

---

## **🤖 Model Performance**

| **Model**           | **Accuracy** | **F1 Score** | **Notes**                 |
|----------------------|--------------|--------------|---------------------------|
| Logistic Regression  | 93.4%        | 0.34         | Baseline                  |
| Random Forest (Tuned)| 92.2%        | 0.58         | Best performance achieved |
| SMOTETomek + RF      | 91.8%        | 0.53         | Improved recall           |

---

## **📊 Dashboard Insights**
- **Demographics**: Age and job type are strong predictors.  
- **Call Duration**: Effective engagement drives subscriptions.  
- **Contact Month**: Subscriptions peak in May and April.

![Dashboard Insights](https://github.com/akashBhaiya/5995/blob/main/Screenshot%202025-01-19%20024120.png)

---

## **📌 Results**
- **Best Model**: Random Forest with hyperparameter tuning (F1 Score: 0.58).  
- **Test Predictions**: Exported in `5995.csv` for leaderboard submission.

![AccuracyScore](https://github.com/akashBhaiya/5995/blob/main/accuracy_score.png)  
![Full_Report](https://github.com/akashBhaiya/5995/blob/main/detail_report.png)
*Streamlit app for predictions and insights.*

---

## **🔮 Future Enhancements**
- Implement advanced models like LightGBM and CatBoost for better accuracy and F1 Score.
- Automate feature engineering for efficiency and consistency.
- Deploy the solution in a cloud environment for real-time predictions.

---

## **👥 Group Members**

1. **Krishna**  
   [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/krushna-chandra-nayak-b18a55176/)  
   **Email**: krishnaintoit@gmail.com  

2. **Nisha**  
   [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nisha-rana-185189216/)  
   **Email**: nisharanakv123@gmail.com

3. **Akash**  
   [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](http://www.linkedin.com/in/akash-vishwakarma-396b89210)  
   **Email**: akashvishwakarmaav84@gmail.com

--- 
