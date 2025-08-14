# Bank Marketing Prediction

This project predicts whether a client will subscribe to a bank term deposit using machine learning models trained on the UCI Bank Marketing dataset.

## Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/222/bank+marketing)  
- Instances: 45,211 | Features: 17  
- Target variable: `y` (subscription: yes/no)  

## Features
- Customer attributes: age, job, marital status, education, credit info, loans, balance  
- Campaign info: contact type, day, month, duration, number of contacts, previous campaign outcome  

## Data Preprocessing
- Encoding categorical variables (One-Hot, Ordinal)  
- Handling missing/invalid values via mode/median imputation  
- Feature interactions for predictive enhancement  

## Models Trained
- Decision Tree  
- Logistic Regression  
- Random Forest    

## Model Evaluation
| Model               | Accuracy | F1 Score | AUC  |
|--------------------|---------|----------|------|
| Random Forest       | 88%     | 0.39     | 0.77 |
| Logistic Regression | 83%     | 0.41     | 0.75 |
| Decision Tree       | 82%     | 0.32     | 0.62 |

- Random Forest was found to be the most effective model for identifying potential subscribers.  

## Practical Implications
- Guides marketing efforts toward clients most likely to subscribe  
- Reduces wasted resources and improves campaign efficiency  
- Periodic retraining recommended to maintain accuracy  

## Next Steps
- Deploy Random Forest in production  
- Monitor performance metrics: Accuracy, F1-score, AUC  
- Explore Gradient Boosting/XGBoost for additional improvements  

## References
- Moro, S., Cortez, P., & Rita, P. (2014). A data-driven approach to predict the success of bank telemarketing. Decision Support Systems.  
- UCI Machine Learning Repository. Bank Marketing Dataset. https://archive.ics.uci.edu/dataset/222/bank+marketing  
- Odo, C. (2023). Random Forest: Assumptions, Advantages, Disadvantages and Applications. Medium. https://medium.com/@chibuike.odo.c/random-forest-assumptions-advantages-disadvantages-and-applications-2881f4ea14b6  
- Additional references in APA format.
