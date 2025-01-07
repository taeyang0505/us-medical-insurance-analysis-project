# us-medical-insurance-analysis-project
Investigating a medical insurance costs dataset using Python skills.

## 1. Project Overview
- This project aims to analyze factors affecting medical insurance costs in the United States.
- Using the `insurance.csv` dataset, we explored key variables like age, BMI, and smoking habits.
- A linear regression model was implemented to predict insurance costs.

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
- Smoking status has the most significant impact on insurance costs.
- The linear regression model achieved an R-squared value of 0.74.

## 4. How to Run
- Clone this repository:
  ```bash
  git clone https://github.com/taeyang0505/us-medical-insurance-analysis-project.git
  cd us-medical-insurance-analysis-project

Follow these steps to set up and run the project:

1.Clone this repository:
	•	Run the following commands in your terminal:
	 •	git clone https://github.com/taeyang0505/us-medical-insurance-analysis-project.git
	 •	cd us-medical-insurance-analysis-project
 
2.Install required libraries:
	•	Run the following command:
	 •	pip install pandas numpy matplotlib seaborn scikit-learn
 
3.Run the project in Jupyter Lab:
	•	Start Jupyter Lab by running:
	 •	jupyter lab
	 •	Open the file us-medical-insurance-costs.ipynb and execute the cells step-by-step.


## 5. Project Structure
The repository is organized as follows:
us-medical-insurance-analysis-project/
├── insurance.csv                # Dataset file
├── us-medical-insurance.ipynb   # Jupyter Notebook for analysis
├── README.md                    # Project description
├── insurance_predictions.csv    # Model prediction results


## 6. Objectives
- Identify key factors affecting medical insurance costs.
- Use data visualization to gain insights into the dataset.
- Build a machine learning model to predict insurance costs based on key variables.


## 7. Conclusions and Future Work
- **Key Findings**:
  - Smoking status has the greatest impact on insurance costs.
  - Age and BMI are also significant factors affecting charges.

- **Future Improvements**:
  - Explore more complex models like Random Forest or Gradient Boosting.
  - Incorporate additional variables (e.g., income, occupation) for better predictions.
    
