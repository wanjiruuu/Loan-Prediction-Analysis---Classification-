# Bank Credit Status Classification/Prediction

### Dataset information
It is a dataset describing bank credit status of clients.

### Project Summary 

This project addresses critical challenges in financial lending by analyzing a loan dataset to predict/classify loan status. The dataset contains 100,000 observations across 19 variables, including borrower demographics and loan characteristics.

Data preparation included handling missing values, removing duplicates, and addressing outliers in income and employment length. We used pandas for data manipulation and scikit-learn for preprocessing, applying StandardScaler for feature scaling and LabelEncoder for categorical variables.

For credit status prediction, multiple models were tested such as Logistic Regression, Decision Trees, Random Forest with cross validation. Random Forest proved most effective, achieving 91.06% accuracy. 

Model performance was assessed using an 80-20 train-test split, with metrics such as accuracy, precision, and recall for classification.


## Business Understanding
With the growing significance of consumer credit and lending, accurate and efficient credit risk assessment is crucial for both financial institutions and customers. These assessments safeguard banks' financial health, increase credit volume, and promote responsible lending, ensuring economic stability and loans for reliable borrowers. Misjudging a borrower’s risk can lead to losses for institutions, while inaccurate loan amounts may either overburden the customer or limit their potential.

Credit risk classification segments borrowers based on their creditworthiness, influencing loan approvals and interest rates. 

By applying machine learning, lenders can balance credit access with maintaining a healthy loan portfolio, benefiting both borrowers and financial institutions.


### Stakeholders
- Financial Institutions (e.g., Banks, Credit Unions): Responsible for managing lending and risk.
- Loan Applicants: Borrowers seeking loans for various purposes.
- Credit Bureaus: Agencies managing credit reports.
- Investors & Shareholders: Those with stakes in financial institutions.
- Regulatory Bodies: Ensuring compliance in lending practices.
- Loan Officers: Individuals assessing loan eligibility.


**Aim** is to develop a model to predict/classify loan status that can be applied.

This is a standard supervised classification task.

## Libraries 
* Pandas
* matplotlib
* seaborn
* scikit-learn

## Algorithms
* Logistic Regression
* Decision Tree
* RandomForest

## Key Results

- **RandomForest** achieved high precision (89.2%) in identifying default loans.

## Key Findings

### 1. Borrower Profiles and Loan Intentions
- Many loans were taken for **debt consolidation purposes** implying the economy is quite bad.
- A significant portion of borrowers have **home morgages**, not homeowners.

### 2. Model Performance
- **RandomForest** models outperformed other algorithms for  **Credit status Classification**: Achieved 90% accuracy and 89% precision.
- **Hyperparameter tuning** did not significantly improve performance, suggesting RandomForest performs well with default settings.

### 5. Feature Importance
- Key features for loan outcomes include:
  - **Borrower income**
  - **Recommendation**: Financial institutions can refine their credit policies using these insights to better understand borrower behavior and risk.

## Recommendations for Financial Institutions
1. **Custom Loan Products**: Develop loan offerings tailored to specific borrower segments, such as young professionals and education seekers.
2. **Enhance Risk Assessment**: Incorporate machine learning models like RandomForest to predict credit risk with high accuracy.
3. **Financial Literacy Programs**: Educate borrowers to reduce default rates and promote healthier financial habits.
4. **Continuous Model Monitoring**: Regularly update models with new borrower data to maintain accuracy and relevance.
5. **Advanced Techniques**: Explore ensemble learning methods to improve credit risk prediction models.

This project demonstrates the power of machine learning in revolutionizing credit risk assessment. By adopting these techniques, financial institutions can make more informed decisions, reduce default rates, and better serve diverse borrower profiles. Continued investment in machine learning and AI technologies will be key to optimizing financial services and driving sustainable growth.
