# **Practice-Capstone-Project**  
**Completing the Home Credit Default Risk Competition on Kaggle**  
[Link to competition](https://www.kaggle.com/competitions/home-credit-default-risk)  

---

## **Business Problem and Project Objective**  
Home Credit faces significant challenges in accurately predicting the repayment ability of individuals with limited or no traditional credit history. This results in underserved individuals either being rejected or subjected to predatory lending practices. The project aimed to improve Home Credit's predictive models by leveraging alternative data such as telco and transactional information. Enhanced accuracy allows Home Credit to responsibly expand its client base, minimize default rates, offer safer loan options, and increase profitability while promoting financial inclusivity.  

---

## **Solution to the Business Problem**  
Our team addressed the problem by cleaning missing data, removing irrelevant variables, and adjusting for dataset imbalance. We tested multiple models, including an Ensemble Model (LightGBM), SVM models (with SMOTE and without), and a Linear Regression model. The final results demonstrated the predictive power of these approaches:  

- **SVM Model**: Kaggle Score: `0.58357`  
- **Linear Regression (Classification)**: Kaggle Score: `0.73867`  
- **LightGBM Model**: Kaggle Score: `0.74085`  

The LightGBM model emerged as the most effective, with high accuracy for predicting loan default probability. The linear regression model provided a transparent and adaptable framework for potential real-time implementation.  

---

## **Business Value of the Solution**  
The LightGBM model enables Home Credit to analyze critical features beyond traditional credit scores, enhancing decision-making and risk assessment. Meanwhile, the linear regression model offers a straightforward pipeline solution for real-time evaluations, empowering analysts with an interpretable and customizable tool. Together, these solutions improve Home Credit’s ability to responsibly expand its client base, reduce defaults, and drive profitability.  

---

## **Difficulties Encountered**  
Our group faced challenges in determining the programming language to use, exporting Kaggle results for SVM and Linear models, and effectively translating analytical findings into a business context during our final presentation.  

---

## **What I Learned**  
This project highlighted the importance of collaboration in tackling data problems, showing that leveraging teammates’ strengths fosters success. Balancing the complexities of multiple models was insightful yet time-consuming, underscoring the need for thoughtful prioritization. Additionally, effective communication and teamwork proved essential in ensuring clarity and alignment throughout the project.  
