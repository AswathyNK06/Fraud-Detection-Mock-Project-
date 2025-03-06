# Fraud Detection (Mock Project)

## Exploratory Analysis, Model Evaluation, Fraud Detection Rules, and Fraud Prevention Recommendations

## Project Goal
This project focuses on developing a structured fraud detection strategy using data analysis, machine learning, and rule-based detection. The analysis includes:

- **Data Cleaning & Preprocessing**
- **Exploratory Data Analysis (EDA)**
- **Comparison of Old vs. New Fraud Detection Models**
- **Evaluation of Fraud Prevention Rules**
- **Business Recommendations for Fraud Prevention**

This is a **mock project** based on an **anonymized dataset** reflecting fraud patterns in an online transaction environment.

## Technologies Used
- **Programming:** Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- **Machine Learning:** Logistic Regression, Model Evaluation (AUC-ROC, Precision-Recall)
- **Data Processing:** Data Cleaning, Feature Engineering, SMOTE (Synthetic Minority Oversampling)
- **Visualization:** Matplotlib, Seaborn
- **Notebook & Report:** Jupyter Notebook (`.ipynb`), PDF Report (`.pdf`)

## Dataset Information
The dataset used for this project is **anonymized and simulated** for fraud detection analysis. It contains transaction-related features and fraud model scores used for evaluation. 

- **Fraud Class Distribution:** The dataset is imbalanced, requiring resampling techniques.
- **Key Features:** Fraud detection model scores, transaction details, user behavior patterns.
- **Data Processing Steps:** Data cleaning, handling missing values, feature selection.

*Note: The dataset is used purely for educational and demonstration purposes.*

## How to Run the Notebook
1. **Clone the Repository**
   ```
   git clone https://github.com/AswathyNK06/Fraud-Detection-Mock-Project.git
   cd Fraud-Detection-Mock-Project
   ```

2. **Install Dependencies (if not installed)**
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

3. **Open Jupyter Notebook**
   ```
   jupyter notebook
   ```
   - Navigate to `fraud_detection_analysis.ipynb` and open it.

4. **Run All Cells** to see the analysis.

## Key Findings
- **New fraud detection model performs better** than the old one in separating fraud from genuine transactions.
- **Fraudulent activities peak during specific time periods and days**, requiring enhanced monitoring.
- **Fraud prevention rules were evaluated**:
  - **Rule A (High Precision):** Captures fraud accurately but may miss some cases.
  - **Rule D (High Recall):** Detects more fraud but has a higher false positive rate.
- **Business Recommendation:** A hybrid fraud detection strategy combining **machine learning models and rule-based detection** is ideal.

## Report & Insights
A detailed fraud detection analysis report is available in this repository:  
📄 **[Fraud Detection Analysis Report.pdf](Fraud%20Detection%20Analysis%20Report.pdf)**

## Next Steps
- Improve fraud detection models with additional feature engineering.
- Optimize fraud score thresholds for better accuracy.
- Test real-time fraud detection strategies.

## Connect & Explore
If you find this project useful, feel free to explore, contribute, or share feedback.

