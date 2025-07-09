# LostCirculationTypes
This repository presents an explainable multi-classification framework for lost circulation type identification, integrating CatBoost, SMOTENC, and SHAP-based interpretability. The code includes preprocessing, model comparison, class balancing, and multi-level explanation.

## Project Scope

The project aims to develop an explainable and robust multi-classification model for lost circulation type identification in drilling operations. The approach integrates **CatBoost**, **SMOTENC** (Synthetic Minority Over-sampling Technique for Nominal and Continuous variables), and **SHAP** interpretability methods to address the challenges of small sample size, class imbalance, and limited transparency in real-world datasets.

All core code is written and organized in **Jupyter Notebooks** for ease of execution and reproducibility.

## Project Structure

The code is divided into five main parts:

### 1. Data Preprocessing
- **1.1 Data Imputation**  
  Handling missing values using appropriate strategies for numerical and categorical variables.
- **1.2 Correlation Analysis**  
  Exploring relationships between input features and target classes using statistical and visual tools.

### 2. Model Comparison
- Baseline comparisons between **CatBoost** and **LightGBM** under high-dimensional, small-sample conditions.

### 3. CatBoost
- Training and evaluation of the CatBoost multi-class classifier for lost circulation type prediction.

### 4. SMOTENC
- Applying SMOTENC to enhance minority class representation and mitigate class imbalance.

### 5. SHAP-Based Interpretability
- **5.1 Global-Level Interpretation**  
  Identifying globally important features across all samples.
- **5.2 Class-Level Interpretation**  
  Analyzing feature contributions within each lost circulation type.
- **5.3 Sample-Level Interpretation**  
  Providing detailed explanations for individual predictions to support decision-making.

## Notes

- The dataset used in this study is **not publicly available** due to confidentiality agreements.
- This repository contains only the source code and can be freely reused for academic or educational purposes.

## Contact

For questions or collaboration, please contact:  
`Huayan Mu` – *China University of Petroleum (Beijing), College of Artificial Intelligence*  
Email: `huayanmu5@gmail.com`

---


