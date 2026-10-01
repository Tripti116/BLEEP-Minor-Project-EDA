

\# Student Performance \& Academic Analytics



\## BLEEP Education – Artificial Intelligence Internship



\*\*Student:\*\* Tripti  

\*\*Course:\*\* B.Tech CSE – Artificial Intelligence \& Machine Learning  

\*\*Institution:\*\* SRM Institute of Science and Technology  

\*\*Internship:\*\* BLEEP Education – Artificial Intelligence, June Batch  

\*\*Project Type:\*\* Exploratory Data Analysis (EDA)



\---



\## 1. Project Overview



The \*\*Student Performance \& Academic Analytics\*\* project focuses on performing Exploratory Data Analysis (EDA) on student academic and demographic data.



The project analyzes factors such as study time, previous failures, absences, parental education, internet access, gender, and other student characteristics to understand their relationship with final academic performance.



The analysis includes data understanding, data quality checks, statistical analysis, visualization, correlation analysis, and outlier detection.



\---



\## 2. Objectives



\- Understand the structure and characteristics of the student dataset.

\- Identify missing values, duplicate records, and invalid values.

\- Analyze numerical and categorical features.

\- Study the distribution of student grades and other variables.

\- Investigate relationships between student characteristics and academic performance.

\- Analyze correlations between numerical features.

\- Detect potential outliers using the IQR method.

\- Generate meaningful visualizations and interpret the findings.

\- Identify factors associated with final student performance.



\---



\## 3. Dataset



The project uses the \*\*Student Performance Dataset\*\* from the UCI Machine Learning Repository.



\### Dataset Used



\*\*File:\*\* `student-mat.csv`



The dataset contains student information related to mathematics performance.



\### Target Variable



\- \*\*G3\*\* – Final grade of the student, measured on a scale of 0–20.



\### Important Features



| Feature | Description |

|---|---|

| `school` | Student's school |

| `sex` | Student's gender |

| `age` | Student's age |

| `address` | Student's residential area |

| `famsize` | Family size |

| `Pstatus` | Parent cohabitation status |

| `Medu` | Mother's education |

| `Fedu` | Father's education |

| `studytime` | Weekly study time |

| `failures` | Number of past class failures |

| `schoolsup` | Extra educational support |

| `famsup` | Family educational support |

| `internet` | Internet access at home |

| `absences` | Number of school absences |

| `G1` | First-period grade |

| `G2` | Second-period grade |

| `G3` | Final grade |



\---



\## 4. Data Understanding



The dataset was examined using:



\- Number of rows and columns

\- Data types

\- Descriptive statistics

\- Numerical feature identification

\- Categorical feature identification

\- Unique-value analysis

\- Dataset-specific data dictionary



The analysis separates numerical and categorical variables to apply appropriate statistical and visualization techniques.



\---



\## 5. Data Quality \& Cleaning



The following data quality checks were performed:



\### Missing Values



The dataset was checked for missing values across all columns.



\### Duplicate Records



Duplicate rows were identified and checked before analysis.



\### Data Types



Data types of all variables were inspected to ensure appropriate analysis.



\### Validity Checks



Ranges and unique values were examined for important variables such as:



\- Age

\- G1

\- G2

\- G3

\- Absences

\- Study time

\- Previous failures



\### Outlier Detection



Potential outliers were identified using the \*\*Interquartile Range (IQR)\*\* method.



The analysis focused on:



\- Age

\- Absences

\- G1

\- G2

\- G3



Outliers were analyzed as potential unusual observations rather than automatically removed.



\---



\## 6. Exploratory Data Analysis



The project includes the following types of analysis:



\### Univariate Analysis



Individual variables were analyzed using:



\- Histograms

\- Count plots

\- Box plots

\- Distribution analysis



\### Bivariate Analysis



Relationships between two variables were analyzed using:



\- Bar charts

\- Scatter plots

\- Grouped comparisons

\- Average grade comparisons



\### Multivariate Analysis



Multiple numerical variables were analyzed using:



\- Correlation matrix

\- Correlation heatmap

\- Feature relationships



\---



\## 7. Visualizations



The project includes the required EDA visualizations:



\### Histograms



\- Final Grade (`G3`) distribution

\- Absences distribution

\- Study time distribution



\### Box Plots



\- Final Grade (`G3`)

\- Absences

\- Age



\### Bar Charts



\- Average final grade by gender

\- Average final grade by study time

\- Average final grade by previous failures



\### Count Plots



\- Gender distribution

\- School distribution



\### Scatter Plots



\- Absences vs Final Grade

\- Study Time vs Final Grade



\### Correlation Heatmap



A correlation heatmap was created to examine relationships among numerical features.



\### Additional Visualizations



\- Average final grade by mother's education

\- Average final grade by internet access



Each visualization is accompanied by an interpretation in the notebook.



\---



\## 8. Correlation Analysis



Correlation analysis was performed on numerical variables to identify relationships between student characteristics and final grade (`G3`).



The correlation values were examined to understand which numerical variables show stronger or weaker associations with final academic performance.



Correlation indicates association and does not establish causation.



\---



\## 9. Key Findings



The EDA provides insights into:



\- The distribution of students' final grades.

\- The relationship between previous failures and final academic performance.

\- The relationship between study time and final grades.

\- The association between absences and final grades.

\- Differences in average performance across demographic groups.

\- The relationship between parental education and student performance.

\- The association between internet access and academic performance.

\- Relationships among numerical academic and demographic variables.

\- Potential outliers in grades, absences, and age.



These findings represent patterns and associations observed in the dataset and should not be interpreted as proof of causation.



\---



\## 10. Time-Series Analysis



A time-series analysis was \*\*not applicable\*\* to this dataset because it does not contain a suitable time-based variable for chronological analysis.



\---



\## 11. Project Workflow



```text

Dataset

&#x20;  ↓

Data Loading

&#x20;  ↓

Data Understanding

&#x20;  ↓

Data Quality Checks

&#x20;  ↓

Missing Value Analysis

&#x20;  ↓

Duplicate \& Validity Checks

&#x20;  ↓

Outlier Detection

&#x20;  ↓

Univariate Analysis

&#x20;  ↓

Bivariate Analysis

&#x20;  ↓

Multivariate Analysis

&#x20;  ↓

Correlation Analysis

&#x20;  ↓

Visualization \& Interpretation

&#x20;  ↓

Key Findings

&#x20;  ↓

Conclusion \& Future Scope

````



\---



\## 12. Technologies \& Tools Used



\* \*\*Python\*\*

\* \*\*Pandas\*\*

\* \*\*NumPy\*\*

\* \*\*Matplotlib\*\*

\* \*\*Seaborn\*\*

\* \*\*Jupyter Notebook\*\*

\* \*\*Git \& GitHub\*\*



\---



\## 13. Project Structure



```text

Student Performance \& Academic Analytics/

│

├── student-mat.csv

├── Student\_Performance\_Analytics.ipynb

└── README.md

```



\---



\## 14. Conclusion



The \*\*Student Performance \& Academic Analytics\*\* project demonstrates a complete Exploratory Data Analysis workflow on student performance data.



The project covers:



\* Data understanding

\* Data cleaning and quality checks

\* Missing value analysis

\* Duplicate detection

\* Validity checks

\* Outlier detection

\* Univariate analysis

\* Bivariate analysis

\* Multivariate analysis

\* Correlation analysis

\* Data visualization

\* Interpretation of findings



The analysis provides a structured understanding of the factors associated with student academic performance and creates a foundation for further statistical analysis and predictive modeling.



\---



\## 15. Future Scope



The project can be extended by:



\* Performing deeper statistical analysis.

\* Identifying important predictors of final academic performance.

\* Applying feature engineering techniques.

\* Building machine learning models for student performance prediction.

\* Comparing different machine learning algorithms.

\* Evaluating model performance using suitable metrics.

\* Applying explainable AI techniques to understand model predictions.



\---



\## 16. Internship Context



This project was completed as part of the \*\*BLEEP Education – Artificial Intelligence Internship, June Batch\*\*.



It demonstrates the application of Python-based data analysis, visualization, statistical exploration, and Exploratory Data Analysis techniques covered during the internship.



\---



\## 17. Author



\*\*Tripti\*\*

B.Tech CSE – Artificial Intelligence \& Machine Learning

SRM Institute of Science and Technology



```

```



