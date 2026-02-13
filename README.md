# task2_titanic-dataset_EDA

# 🚢 Task 2: Exploratory Data Analysis (EDA) -- Titanic Dataset

## 📌 Objective

The objective of this task is to perform Exploratory Data Analysis (EDA)
on the Titanic dataset to understand the data through descriptive
statistics and visualizations. The goal is to uncover patterns,
relationships, trends, and anomalies before applying machine learning
models.

------------------------------------------------------------------------

## 🛠 Tools & Technologies Used

-   Python\
-   Pandas\
-   NumPy\
-   Matplotlib\
-   Seaborn\
-   Jupyter Notebook

------------------------------------------------------------------------

## 📂 Dataset

**Dataset Name:** Titanic Dataset (Cleaned Version)

This dataset was preprocessed in Task 1 where: - Missing values were
handled\
- Categorical variables were encoded\
- Irrelevant columns were removed\
- Data was prepared for analysis

The cleaned dataset was used for performing EDA.

------------------------------------------------------------------------

## 🔎 Steps Performed in EDA

### 1️⃣ Data Overview

-   Checked dataset shape
-   Verified data types
-   Reviewed summary statistics using describe()

------------------------------------------------------------------------

### 2️⃣ Descriptive Statistics

Generated: - Mean\
- Median\
- Standard deviation\
- Minimum and maximum values

Key Observations: - Survival rate shows imbalance between survived and
non-survived passengers. - Fare has high variance indicating large
differences in ticket pricing. - Age is moderately distributed across
passengers.

------------------------------------------------------------------------

### 3️⃣ Histograms

Histograms were created for numeric features to understand
distributions.

Findings: - Age shows moderate distribution with slight skewness. - Fare
is highly right-skewed due to a small number of extremely high ticket
prices. - Majority of passengers belong to 3rd class.

------------------------------------------------------------------------

### 4️⃣ Boxplots (Outlier Detection)

Boxplots were used to identify outliers.

Findings: - Fare contains significant extreme values. - Age shows mild
outliers. - High fare values indicate economic inequality among
passengers.

------------------------------------------------------------------------

### 5️⃣ Survival Analysis

#### Survival by Gender

-   Females had significantly higher survival rates than males.
-   Gender strongly influenced survival probability.

#### Survival by Passenger Class

-   1st class passengers had the highest survival rate.
-   3rd class passengers had the lowest survival rate.
-   Socio-economic status played a major role in survival outcomes.

------------------------------------------------------------------------

### 6️⃣ Correlation Analysis

A correlation heatmap was generated to examine relationships between
numeric features.

Key Insights: - Strong negative correlation between Pclass and Fare. -
Noticeable relationship between Sex and Survived. - No severe
multicollinearity detected among independent features.

------------------------------------------------------------------------

### 7️⃣ Skewness Analysis

-   Fare shows strong positive skewness.
-   Age shows moderate skewness.
-   Skewed features may require transformation before model training.

------------------------------------------------------------------------

## 📊 Key Insights from EDA

1.  Gender is a strong predictor of survival.
2.  Passenger class significantly influenced survival probability.
3.  Fare distribution is heavily skewed due to extreme values.
4.  Socio-economic differences impacted survival outcomes.
5.  Dataset contains imbalance in survival classes.

------------------------------------------------------------------------

## 🎯 Conclusion

Exploratory Data Analysis provided a deep understanding of the dataset
before modeling.\
Important patterns such as gender influence, class disparity, fare
skewness, and survival imbalance were identified.

Performing EDA ensures informed decision-making during feature selection
and model building.

------------------------------------------------------------------------

## 📁 Repository Structure

Task-2-EDA-Titanic/ │ ├── Titanic-Dataset-cleaned.csv ├──
Task2_EDA.ipynb ├── README.md └── Screenshots/

------------------------------------------------------------------------

## 📌 Future Scope

-   Feature engineering based on insights\
-   Handling class imbalance before modeling\
-   Building classification models for survival prediction
