# us-medical-insurance-analysis-project
Investigating a medical insurance costs dataset using Python skills.

## 1. Project Overview
- This project aims to analyze factors affecting medical insurance costs in the United States.
- Using the `insurance.csv` dataset, we explored key variables like age, BMI, and smoking habits.
- Various machine learning models, including Linear Regression, Random Forest, Gradient Boosting, and Ensemble Methods, were implemented to predict insurance costs.

## 2. Dataset
- **Columns**:
  - `age`: Age of the individual.
  - `sex`: Gender (`male`, `female`).
  - `bmi`: Body mass index.
  - `children`: Number of dependents.
  - `smoker`: Smoking status (`yes`, `no`).
  - `region`: Residential area in the US.
  - `charges`: Insurance charges (target variable).

## 3. Key Results
3.1 Insights
- Smoking status has the most significant impact on insurance costs.
- The linear regression model achieved an R-squared value of 0.74.
- Gradient Boosting achieved the best predictive accuracy among the tested models.

3.2 Model Performance:

Mean Squared Error (MSE):
  - Gradient Boosting: 18,806,526.04
  - Ensemble (Voting): 18,984,836.56
	- Pipeline RF Model: 19,980,284.73
R² Score:
	- Gradient Boosting: 0.8789
	- Ensemble (Voting): 0.8777
	- Pipeline RF Model: 0.8713

## 4. How to Run
- Clone this repository:
  ```bash
  git clone https://github.com/taeyang0505/us-medical-insurance-analysis-project.git
  cd us-medical-insurance-analysis-project


## 5. Project Structure
The repository is organized as follows:

```
us-medical-insurance-analysis-project/
├── insurance.csv                # Dataset file
├── us-medical-insurance.ipynb   # Jupyter Notebook for analysis
├── README.md                    # Project description
├── insurance_predictions.csv    # Model prediction results
```

## 6. Objectives
- Identify key factors affecting medical insurance costs.
- Use data visualization to gain insights into the dataset.
- Build a machine learning model to predict insurance costs based on key variables.
  - Linear Regression
  - Random Forest
  - Gradient Boosting
  - Ensemble (Voting Regressor)
- Highlight feature importance using Random Forest and Gradient Boosting.

## 7. Conclusions and Future Work
- **Key Findings**:
  - Smoking status has the greatest impact on insurance costs.
  - Age and BMI are also significant factors affecting charges.
  - Random Forest and Gradient Boosting outperform Linear Regression in predictive accuracy.

- **Future Improvements**:
  - Advanced Models: Explore more complex models such as Neural Networks.
  - Additional Features: Incorporate variables like income and occupation for enhanced predictions.
  - Hyperparameter Tuning: Further optimize Random Forest and Gradient Boosting models for better performance.
    
