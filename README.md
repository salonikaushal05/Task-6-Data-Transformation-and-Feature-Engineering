# Task-6-Data-Transformation-and-Feature-Engineering
Data Transformation and Feature Engineering on a Housing Dataset using Python, Pandas, and Scikit-learn. Includes missing value handling, one-hot encoding, feature scaling, interaction feature creation, and generation of a machine-learning-ready dataset.

This project was completed as part of the Data Analytics Internship program. The objective was to transform and enhance a housing dataset using feature engineering techniques to make it suitable for machine learning models.

The project focuses on handling missing values, encoding categorical variables, scaling numerical features, and creating interaction features.

##  Objective

To improve data quality and prepare a housing dataset for predictive modeling through data transformation and feature engineering techniques.

##  Tools & Technologies Used

- Python
- Pandas
- Scikit-learn
- Jupyter Notebook


##  Dataset

**Dataset:** Housing Dataset (House Prices)

The dataset contains various housing attributes such as property size, quality, neighborhood, construction details, and sale price.

---

##  Feature Engineering Techniques Applied

### 1. Missing Value Handling
Missing values were identified and treated using:
- Median Imputation for numerical features
- Mode Imputation for categorical features

### 2. One-Hot Encoding
Categorical variables were converted into numerical binary columns using Pandas `get_dummies()`.

### 3. Feature Scaling
Numerical features were standardized using `StandardScaler`.

Benefits:
- Mean centered around 0
- Standard deviation scaled to 1
- Improved model performance

### 4. Interaction Feature Creation
A new interaction feature was created:

```python
Quality_Area_Interaction = OverallQual * GrLivArea
```

This feature captures the combined impact of house quality and living area.

---

## 📈 Results

### Original Dataset
- Rows: 1460
- Columns: 81

### Engineered Dataset
- Rows: 1460
- Columns: 247

### Transformations Performed
✅ Missing Value Treatment

✅ One-Hot Encoding

✅ Feature Scaling

✅ Interaction Feature Engineering

## Key Insights

- The dataset contained several missing values that were successfully treated.
- One-Hot Encoding increased the number of features from 81 to 247.
- Feature scaling standardized numerical variables.
- Interaction features improved feature representation.
- The final dataset became fully numerical and ready for machine learning applications.

---

##  Conclusion

The housing dataset was successfully transformed using various feature engineering techniques. The resulting engineered dataset is cleaner, more informative, and suitable for machine learning model development.

This project demonstrates the importance of preprocessing and feature engineering in the data analytics and machine learning workflow.

---

##  Outcome

Successfully enhanced a housing dataset for predictive modeling using Pandas and Scikit-learn by applying data transformation and feature engineering techniques.

---

##  Author

**Saloni Kaushal**  
Data Analytics Intern
