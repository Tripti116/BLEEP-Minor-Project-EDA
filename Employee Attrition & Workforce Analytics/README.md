\# BLEEP Education – Employee Attrition EDA



\## 📌 Project Overview



This project was completed as part of the \*\*BLEEP Education Internship Program – Artificial Intelligence, June Batch\*\*.



The project focuses on \*\*Exploratory Data Analysis (EDA)\*\* of the IBM HR Analytics Employee Attrition \& Performance Dataset. The main goal is to understand the dataset, identify employee-related patterns, analyze factors associated with attrition, and present findings through meaningful visualizations.



> \*\*Note:\*\* This project focuses on Data Understanding and Exploratory Data Analysis and does not include machine learning model development.



\---



\## 🎓 Internship Details



| Detail           | Information                |

| ---------------- | -------------------------- |

| \*\*Program\*\*      | BLEEP Education Internship |

| \*\*Domain\*\*       | Artificial Intelligence    |

| \*\*Batch\*\*        | June Batch                 |

| \*\*Project Type\*\* | Exploratory Data Analysis  |

| \*\*Author\*\*       | Tripti                     |



\---



\## 🎯 Objectives



\* Understand the structure and characteristics of the dataset.

\* Identify numerical and categorical features.

\* Analyze employee attrition distribution.

\* Explore relationships between employee attributes and attrition.

\* Visualize important patterns using graphs and plots.

\* Identify potential outliers in numerical features.

\* Analyze correlations between numerical variables.

\* Extract meaningful HR-related insights from the data.



\---



\## 📊 Dataset



\*\*IBM HR Analytics Employee Attrition \& Performance Dataset\*\*



\### Dataset Information



\* \*\*Records:\*\* 1,470 employees

\* \*\*Original Features:\*\* 35

\* \*\*Target Variable:\*\* `Attrition`

\* \*\*Target Classes:\*\* `Yes` / `No`

\* \*\*Missing Values:\*\* None



\### Important Features



\* Age

\* Department

\* Job Role

\* Job Satisfaction

\* Monthly Income

\* Distance From Home

\* Overtime

\* Years at Company

\* Total Working Years

\* Work-Life Balance

\* Education

\* Education Field

\* Marital Status

\* Gender

\* Performance Rating

\* Business Travel



\---



\## 🧹 Data Cleaning \& Preparation



The following constant or identifier-related columns were removed:



\* `EmployeeCount`

\* `Over18`

\* `StandardHours`

\* `EmployeeNumber`



After removing these columns:



```text

Dataset Shape: (1470, 31)

```



The dataset was then separated into:



\* \*\*Features (`X`)\*\*

\* \*\*Target (`y`)\*\*



Categorical variables were identified and prepared for further analysis using encoding techniques.



\---



\## 🔍 Exploratory Data Analysis



\### 1. Data Understanding



\* Dataset shape

\* Data types

\* Statistical summary

\* Missing-value analysis

\* Unique-value analysis

\* Numerical and categorical feature identification



\### 2. Attrition Analysis



The distribution of employees across:



\* `Attrition = Yes`

\* `Attrition = No`



was analyzed to understand the overall attrition pattern.



\### 3. Categorical Feature Analysis



The relationship between attrition and important categorical variables was explored, including:



\* Overtime

\* Department

\* Job Satisfaction



\### 4. Numerical Feature Analysis



Important numerical variables were analyzed using visualizations, including:



\* Age

\* Monthly Income

\* Distance From Home

\* Years at Company

\* Total Working Years



\### 5. Outlier Analysis



Box plots were used to examine distributions and potential outliers in:



\* Age

\* Monthly Income

\* Distance From Home

\* Years at Company



\### 6. Relationship Analysis



Scatter plots were used to explore:



\* Age vs Monthly Income

\* Years at Company vs Monthly Income



\### 7. Correlation Analysis



A correlation heatmap was used to identify relationships between numerical variables.



\---



\## 💡 Key Insights



\* Employee attrition is unevenly distributed, with fewer employees leaving than staying.

\* Overtime shows a noticeable relationship with employee attrition.

\* Job satisfaction varies across different attrition outcomes.

\* Attrition patterns differ across departments.

\* Age and monthly income distributions provide useful comparisons between employees who stayed and those who left.

\* Distance from home provides additional insight into attrition patterns.

\* Years at company and monthly income show observable relationships.

\* Correlation analysis helps identify relationships among numerical employee attributes.



\---



\## 🛠️ Technologies Used



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Scikit-learn

\* Jupyter Notebook



\---



\## 📁 Project Structure



```text

Employee-Attrition-EDA/

│

├── 01\_Data\_Understanding.ipynb

├── README.md

└── dataset/

&#x20;   └── employee\_attrition\_dataset.csv

```



> The dataset filename may vary depending on the file used in the project.



\---



\## ▶️ How to Run



\### 1. Clone the Repository



```bash

git clone <repository-url>

```



\### 2. Navigate to the Project Folder



```bash

cd Employee-Attrition-EDA

```



\### 3. Install Required Libraries



```bash

pip install pandas numpy matplotlib seaborn scikit-learn jupyter

```



\### 4. Open Jupyter Notebook



```bash

jupyter notebook

```



Open:



```text

01\_Data\_Understanding.ipynb

```



Run the cells sequentially to reproduce the analysis and visualizations.



\---



\## 📌 Project Scope



The project follows the workflow:



\*\*Data → Cleaning → Understanding → Exploration → Visualization → Insights\*\*



The primary focus is \*\*Exploratory Data Analysis and Data Understanding\*\*.



\---



\## 🚀 Future Scope



The analysis can be extended by:



\* Feature engineering

\* Statistical hypothesis testing

\* Employee attrition prediction

\* Machine learning model development

\* Model comparison

\* Feature selection

\* Hyperparameter tuning

\* Interactive HR analytics dashboards



\---



\## 👩‍💻 Author



\*\*Tripti\*\*



\*\*B.Tech – Computer Science Engineering (AI \& ML)\*\*

\*\*SRM Institute of Science and Technology\*\*



\### BLEEP Education Internship



\*\*Artificial Intelligence – June Batch\*\*



