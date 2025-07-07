# 48-hours-bias-challenge
Bias detection, explainability, and mitigation in an AI hiring model.

## Files
- `bias_detection_hiring_model.ipynb` – Full code with SHAP explanations, fairness metrics, and bias mitigation techniques.
- `Bias_Report.pdf` – 2-page summary report
- 
## Project Overview
**Model Used**: Logistic Regression  
**Sensitive Feature**: `Gender` (0 = Female, 1 = Male)  
**Target Variable**: `HiringDecision` (1 = Hire, 0 = No Hire)

## Setup Instructions
1. **Open the notebook in Google Colab**
3. Make sure to run:
   ```python
   !pip install scikit-learn pandas matplotlib seaborn
   !pip install shap
   !pip install fairlearn


4. Follow the cells sequentially to:
-Preprocess the dataset
-Train the model
-Evaluate fairness
-Apply SHAP explainability
-Test two bias mitigation methods (counterfactual augmentation and reweighing)
