# 🏥 Healthcare Data Exploratory Data Analysis (EDA)

<p align="center">

  <img src="https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white" alt="Python Badge"/>
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white" alt="Pandas Badge"/>
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-blue" alt="Matplotlib Badge"/>
  <img src="https://img.shields.io/badge/Seaborn-Statistical%20Visualization-76B900" alt="Seaborn Badge"/>
  <img src="https://img.shields.io/badge/Project-EDA-success" alt="EDA Badge"/>
  
</p>

## 📌 Project Overview

Welcome to my **Healthcare Data Exploratory Data Analysis (EDA)** project!

This project focuses on analyzing a preprocessed healthcare dataset using Python and its popular data analysis and visualization libraries.

Exploratory Data Analysis helps us understand the structure of a dataset, identify patterns, examine distributions, compare categories, and explore relationships between numerical variables.

In this project, I explored healthcare-related information, including patient demographics, medical conditions, admission types, hospital billing amounts, insurance providers, admission dates, and length of stay.

The primary objective is to transform raw data into meaningful insights through statistical analysis and visualizations.

---

## 📑 Table of Contents

Click any section below to navigate directly to it.

- [🎯 Project Objectives](#-project-objectives)
- [📂 Dataset Information](#-dataset-information)
- [🛠️ Technologies Used](#️-technologies-used)
- [📊 Exploratory Data Analysis](#-exploratory-data-analysis)
- [📈 Analysis and Visualizations](#-analysis-and-visualizations)
- [💻 Code Examples](#-code-examples)
- [⚙️ Installation and Setup](#️-installation-and-setup)
- [🚀 How to Run the Project](#-how-to-run-the-project)
- [🔍 Key Questions Explored](#-key-questions-explored)
- [📋 Project Workflow](#-project-workflow)
- [📚 Skills Learned](#-skills-learned)
- [🔮 Future Improvements](#-future-improvements)
- [⚠️ Limitations and Disclaimer](#️-limitations-and-disclaimer)
- [👩‍💻 Author](#-author)

---

## 🎯 Project Objectives

The main objectives of this project are:

- Understand the structure and characteristics of a healthcare dataset.
- Examine the dataset's rows, columns, and data types.
- Analyze patient age and gender distributions.
- Explore the frequency of different medical conditions.
- Compare admission types across medical conditions.
- Understand the distribution of hospital billing amounts.
- Calculate average billing amounts across medical conditions.
- Compare billing amounts across insurance providers.
- Analyze monthly admission patterns using admission dates.
- Explore correlations between age, length of stay, and billing amount.
- Present findings using appropriate data visualizations.

## 📂 Dataset Information

**Dataset name:** Healthcare Preprocessed Dataset

**File name:** `healthcare_preprocessed (1).csv`

| Dataset Property | Details |
|---|---|
| File format | CSV |
| Rows | 54,966 |
| Columns | 18 |
| Domain | Healthcare |
| Analysis type | Exploratory Data Analysis |
| Programming language | Python |

### Dataset Attributes

The dataset contains healthcare-related attributes such as:

| Attribute | Description |
|---|---|
| Age | Age of the patient |
| Gender | Patient's gender |
| Blood Type | Patient's blood group |
| Medical Condition | Recorded medical condition |
| Admission Date | Date of hospital admission |
| Discharge Date | Date of discharge |
| Doctor | Doctor associated with the record |
| Hospital | Hospital associated with the record |
| Insurance Provider | Patient's insurance provider |
| Billing Amount | Hospital billing amount |
| Room Number | Room associated with the record |
| Admission Type | Type of hospital admission |
| Medication | Medication recorded |
| Test Results | Recorded test result category |
| Length of Stay | Duration of the hospital stay |
| Age Group | Categorized age group |
| Admission Urgency | Categorization of admission urgency |

<details>
<summary>📌 Click to understand the dataset</summary>

A healthcare dataset contains information related to patients, hospital visits, medical conditions, and billing.

For example, the `Age` column can help examine the distribution of patient ages, while `Medical Condition` can be used to count records across different conditions.

The `Billing Amount` column can be analyzed using summary statistics and visualizations. Admission and discharge dates can help explore admission timing and length of stay.

The dataset fields describe recorded information. They do not independently establish treatment effectiveness or patient outcomes.

</details>

---

## 🛠️ Technologies Used

### 1. Python

Python is the primary programming language used to perform data analysis.

### 2. Pandas

Pandas is used for loading CSV files, exploring tabular data, grouping records, calculating summary statistics, and handling date columns.

### 3. NumPy

NumPy provides numerical computing functionality and support for working with numerical data.

### 4. Matplotlib

Matplotlib is used to create charts and visualize patterns in the dataset.

### 5. Seaborn

Seaborn is used to create statistical visualizations and correlation heatmaps.

### 6. Jupyter Notebook

Jupyter Notebook provides an interactive environment for writing Python code, executing analysis step by step, and displaying results.

---

## 📊 Exploratory Data Analysis

This project explores several aspects of the healthcare dataset.

<details>
<summary><b>1. Dataset Exploration</b></summary>

The first step is to understand the dataset's structure.

Activities include:

- Loading the CSV file.
- Displaying the first few rows.
- Checking the number of rows and columns.
- Examining column names.
- Checking data types.
- Generating descriptive statistics.

</details>

<details>
<summary><b>2. Patient Demographics</b></summary>

Patient demographics are explored using age and gender information.

Activities include:

- Analyzing age distribution.
- Comparing age distributions by gender.
- Counting records by gender.
- Visualizing demographic patterns.

</details>

<details>
<summary><b>3. Medical Condition Analysis</b></summary>

Medical condition data is explored to understand the frequency of recorded conditions.

Activities include:

- Counting records by medical condition.
- Visualizing condition frequencies.
- Comparing medical condition distributions across gender categories.

</details>

<details>
<summary><b>4. Admission Analysis</b></summary>

Admission records are analyzed to understand the distribution of admission types.

Activities include:

- Counting admission types.
- Comparing admission types across medical conditions.
- Exploring monthly admission counts using admission dates.

</details>

<details>
<summary><b>5. Billing Analysis</b></summary>

Hospital billing amounts are examined using summary statistics and visualizations.

Activities include:

- Visualizing billing amount distributions.
- Comparing billing amounts across medical conditions.
- Calculating average billing amounts by medical condition.
- Comparing billing amounts across insurance providers.
- Calculating average billing amounts by insurance provider.

</details>

<details>
<summary><b>6. Correlation Analysis</b></summary>

Correlation analysis explores relationships between selected numerical variables.

The project examines:

- Age
- Length of stay
- Billing amount

A correlation matrix helps identify the direction and strength of linear relationships between these numerical variables.

</details>

---

## 📈 Analysis and Visualizations

The following analyses are included in the notebook.

| No. | Analysis | Purpose |
|---:|---|---|
| 1 | Age Distribution | Understand patient age patterns |
| 2 | Age by Gender | Compare age distributions across genders |
| 3 | Gender Distribution | Examine record counts by gender |
| 4 | Medical Conditions | Explore the frequency of conditions |
| 5 | Conditions by Gender | Compare recorded conditions across genders |
| 6 | Admission Types | Understand admission category frequencies |
| 7 | Admission by Condition | Compare admission categories across conditions |
| 8 | Billing Distribution | Examine billing amount patterns |
| 9 | Billing by Condition | Compare billing amounts across conditions |
| 10 | Average Billing by Condition | Summarize average billing for each condition |
| 11 | Insurance Provider Analysis | Compare billing across insurance providers |
| 12 | Monthly Admissions | Explore admission counts by month |
| 13 | Correlation Matrix | Explore relationships among numerical variables |

<details>
<summary>📊 What can these visualizations help us understand?</summary>

- **Distribution charts** help show how numerical values are spread.
- **Count charts** help compare the frequency of categories.
- **Grouped comparisons** help examine differences between categories.
- **Monthly summaries** help explore changes in admission counts over time.
- **Correlation heatmaps** help identify linear associations between numerical variables.

The actual conclusions should be based on the charts and numerical outputs generated by the notebook.

</details>

---

## 💻 Code Examples

The following are example snippets demonstrating common operations used in healthcare EDA. They can also be used independently to explore the dataset.

### 1. Import Required Libraries

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

### 2. Load the Dataset

```python
df = pd.read_csv("healthcare_preprocessed (1).csv")

df.head()
```

### 3. Explore Dataset Information

```python
print("Dataset Shape:", df.shape)

print("\nColumn Names:")
print(df.columns)

print("\nData Types:")
print(df.dtypes)

print("\nDataset Information:")
df.info()
```

### 4. Generate Descriptive Statistics

```python
df.describe()
```

This provides descriptive statistics for numerical columns, including count, mean, standard deviation, minimum, maximum, and quartiles.

### 5. Analyze Gender Distribution

```python
gender_counts = df["Gender"].value_counts()

print(gender_counts)

gender_counts.plot(kind="bar", title="Gender Distribution")

plt.xlabel("Gender")
plt.ylabel("Count")
plt.tight_layout()
plt.show()
```

### 6. Analyze Medical Conditions

```python
condition_counts = df["Medical Condition"].value_counts()

print(condition_counts)

condition_counts.plot(
    kind="bar",
    title="Medical Condition Distribution"
)

plt.xlabel("Medical Condition")
plt.ylabel("Count")
plt.xticks(rotation=45)
plt.tight_layout()
plt.show()
```

### 7. Calculate Average Billing Amount by Condition

```python
average_billing = df.groupby(
    "Medical Condition"
)["Billing Amount"].mean()

print(average_billing)
```

### 8. Analyze Monthly Admissions

```python
df["Date of Admission"] = pd.to_datetime(
    df["Date of Admission"],
    errors="coerce"
)

monthly_admissions = (
    df.groupby(df["Date of Admission"].dt.to_period("M"))
    .size()
)

print(monthly_admissions)
```

### 9. Generate a Correlation Matrix

```python
numerical_columns = [
    "Age",
    "Length of Stay",
    "Billing Amount"
]

correlation_matrix = df[
    numerical_columns
].corr()

sns.heatmap(
    correlation_matrix,
    annot=True,
    cmap="coolwarm"
)

plt.title("Correlation Matrix")
plt.tight_layout()
plt.show()
```

> **Important:** These code snippets assume the listed column names exist in the CSV file. If a column name differs in your dataset, use the exact name shown by `df.columns`. The snippets illustrate common EDA operations and do not replace the original notebook's complete analysis.

---

## ⚙️ Installation and Setup

### Prerequisites

Before running the project, make sure you have:

- Python installed on your system.
- Jupyter Notebook or Google Colab.
- The healthcare CSV dataset.
- The project notebook, `EDA_Task_6.ipynb`.

### Install the Required Libraries

Open a terminal or command prompt and run:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Project Folder Structure

Organize the files as follows:

```text
Healthcare-EDA/
│
├── EDA_Task_6.ipynb
├── healthcare_preprocessed (1).csv
└── README.md
```

Keeping the notebook and CSV file in the same folder makes it easier to load the dataset using a relative file path.

---

## 🚀 How to Run the Project

<details>
<summary><b>Option 1: Run using Jupyter Notebook</b></summary>

1. Download the project files.
2. Place the notebook and CSV file in the same folder.
3. Open Command Prompt or a terminal in that folder.
4. Run:

   ```bash
   jupyter notebook
   ```

5. Open `EDA_Task_6.ipynb`.
6. Execute the notebook cells from top to bottom.
7. Review the generated charts, summaries, and analysis results.

</details>

<details>
<summary><b>Option 2: Run using Google Colab</b></summary>

1. Open Google Colab.
2. Upload `EDA_Task_6.ipynb`.
3. Upload the healthcare CSV dataset.
4. Update the dataset file path if necessary.
5. Run the notebook cells sequentially.
6. Review the outputs displayed below each cell.

</details>

<details>
<summary><b>Common Troubleshooting Tips</b></summary>

**FileNotFoundError**

Check whether the CSV file is in the expected folder and whether the filename matches the code.

**ModuleNotFoundError**

Install the missing Python library using `pip install library_name`.

**KeyError**

Check the column name using:

```python
print(df.columns.tolist())
```

**Date conversion issues**

Use `pd.to_datetime()` with `errors="coerce"` to identify invalid date values as missing dates.

</details>

---

## 🔍 Key Questions Explored

This project explores the following questions through data analysis:

1. How are patient ages distributed?
2. How does age distribution differ across gender categories?
3. How many records belong to each gender?
4. Which medical conditions occur most frequently in the dataset?
5. How are recorded medical conditions distributed across gender?
6. Which admission types appear in the dataset?
7. How do admission categories vary across medical conditions?
8. How are hospital billing amounts distributed?
9. How do billing amounts compare across medical conditions?
10. What is the average billing amount for each medical condition?
11. How do billing amounts compare across insurance providers?
12. How do admission counts vary by month?
13. What relationships exist between age, length of stay, and billing amount?

The answers should be interpreted from the actual results produced by the notebook rather than assumed in advance.

---

## 📋 Project Workflow

The project follows this general workflow:

```text
Healthcare Dataset
        |
        v
Load Data Using Pandas
        |
        v
Inspect Rows, Columns and Data Types
        |
        v
Explore Demographics and Medical Conditions
        |
        v
Analyze Admissions and Billing Amounts
        |
        v
Generate Statistical Summaries
        |
        v
Create Data Visualizations
        |
        v
Explore Numerical Correlations
        |
        v
Interpret Findings
```

### Project Completion Checklist

- [x] Load the preprocessed healthcare dataset.
- [x] Explore dataset dimensions and data types.
- [x] Analyze patient demographics.
- [x] Explore medical conditions.
- [x] Analyze admission types.
- [x] Explore billing amounts.
- [x] Compare billing across conditions and providers.
- [x] Examine monthly admission counts.
- [x] Generate a correlation matrix.
- [x] Document the project in a README file.

---

## 📚 Skills Learned

By working on this project, I practiced the following skills:

### Technical Skills

- Python programming.
- Data analysis using Pandas.
- Numerical data handling with NumPy.
- Statistical summaries.
- Data visualization using Matplotlib.
- Statistical plotting using Seaborn.
- Date and time conversion.
- Grouping and aggregating data.
- Correlation analysis.
- Jupyter Notebook workflows.

### Analytical Skills

- Exploring structured datasets.
- Identifying patterns in numerical and categorical data.
- Comparing groups using summary statistics.
- Selecting visualizations to communicate data.
- Interpreting analytical results carefully.

### Data Analyst Skills

This project provides practice with several tasks commonly performed in data analysis:

- Data exploration.
- Descriptive analysis.
- Category-wise comparisons.
- Time-based aggregation.
- Visualization.
- Communicating findings.

---

## 🔮 Future Improvements

The project can be expanded with additional analytical features.

- [ ] Create an interactive healthcare dashboard using Power BI.
- [ ] Add interactive charts using Plotly.
- [ ] Add more detailed missing-value analysis.
- [ ] Investigate potential duplicate records.
- [ ] Explore outliers in billing amounts.
- [ ] Add a detailed report of statistical findings.
- [ ] Compare additional numerical variables.
- [ ] Improve chart formatting and labels.
- [ ] Add a documented data dictionary.
- [ ] Create a dashboard with filters for medical condition, gender, and admission type.

These are possible future improvements and are not necessarily implemented in the current notebook.

---

## ⚠️ Limitations and Disclaimer

- This project is intended for educational purposes and exploratory analysis.
- The findings depend on the quality, completeness, and definitions of the supplied dataset.
- Correlation does not establish causation.
- Billing differences should not automatically be interpreted as differences in treatment quality or medical necessity.
- The analysis should not be used to make clinical decisions.
- Avoid publishing personal or sensitive patient information. Confirm that the dataset is permitted for public sharing before uploading it to GitHub.

---

## 👩‍💻 Author

**Vasundhra**

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization

I am interested in learning how data analysis can transform structured datasets into useful information and support data-driven decision-making.

This project is part of my practical learning journey in Exploratory Data Analysis and Python-based data analytics.

---

## ⭐ Support

If you find this project useful for learning Exploratory Data Analysis, consider giving the repository a ⭐ star on GitHub.

Thank you for visiting my project!

