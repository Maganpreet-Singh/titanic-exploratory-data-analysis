# 🚢 Titanic Exploratory Data Analysis (EDA)

An in-depth **Exploratory Data Analysis (EDA)** project on the famous **Titanic Dataset** using **Python, Pandas, Matplotlib, and Seaborn**.

This project focuses on understanding passenger demographics, identifying survival patterns, handling missing values, performing feature engineering, and extracting meaningful insights through statistical analysis and visualizations.

---

# 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Dataset Description](#-dataset-description)
- [Project Objectives](#-project-objectives)
- [Technologies Used](#-technologies-used)
- [Project Workflow](#-project-workflow)
- [Feature Engineering](#-feature-engineering)
- [Analysis Performed](#-analysis-performed)
- [Key Insights](#-key-insights)
- [Repository Structure](#-repository-structure)
- [How to Run](#-how-to-run)
- [Learning Outcomes](#-learning-outcomes)
- [Future Improvements](#-future-improvements)
- [License](#-license)
- [Author](#-author)

---

# 📖 Project Overview

The Titanic dataset is one of the most widely used datasets for learning **Data Analysis** and **Data Science**.

The primary goal of this project is to perform a **complete Exploratory Data Analysis (EDA)** to understand the dataset before applying any Machine Learning algorithm.

This notebook focuses on:

- Understanding dataset structure
- Exploring numerical and categorical features
- Detecting missing values
- Feature engineering
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Drawing meaningful business insights

> **Note:** This project focuses only on **EDA**. No Machine Learning models have been built.

---

# 📊 Dataset Description

The dataset contains information about passengers aboard the RMS Titanic.

## Original Features

| Feature | Description |
|----------|-------------|
| PassengerId | Unique passenger identifier |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class |
| Name | Passenger name |
| Sex | Gender |
| Age | Passenger age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation |

---

# 🎯 Project Objectives

The objectives of this project are:

- Explore the dataset thoroughly
- Understand the distribution of every feature
- Identify missing values
- Perform feature engineering
- Study relationships between variables
- Visualize important trends
- Generate meaningful insights from the data

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 🔄 Project Workflow

## 1. Import Libraries

Imported all required Python libraries.

---

## 2. Load Dataset

- Loaded Titanic dataset
- Displayed sample records

---

## 3. Dataset Overview

Performed:

- Shape
- Columns
- Data Types
- Missing Values
- Duplicate Values
- Summary Statistics
- Memory Usage

---

## 4. Data Cleaning

Performed:

- Missing value analysis
- Feature engineering
- Removed unnecessary columns
- Data preparation for visualization

---

## 5. Univariate Analysis

Analyzed every important feature individually.

### Numerical Features

- Age
- Fare

### Categorical Features

- Survived
- Pclass
- Sex
- Embarked
- Name
- Ticket
- Cabin
- SibSp
- Parch

Each section includes:

- Statistics
- Visualizations
- Interpretation
- Conclusions

---

# ⚙️ Feature Engineering

Created the following new features:

| Feature | Description |
|----------|-------------|
| Title | Extracted from passenger names |
| Deck | Extracted from Cabin |
| FamilySize | SibSp + Parch + 1 |
| FamilyType | Alone / Small Family / Large Family |
| AgeGroup | Grouped passenger ages |
| FareGroup | Grouped fare values |
| Name_Length | Length of passenger names |
| Word_Count | Number of words in names |
| Cabin_Count | Number of cabins assigned |
| Ticket_Length | Length of ticket number |

---

# 📈 Analysis Performed

## Univariate Analysis

Analyzed:

- Survived
- Passenger Class
- Sex
- Age
- Fare
- Embarked
- Name
- Ticket
- Cabin
- SibSp
- Parch

---

## Bivariate Analysis

Compared Survival with:

- Sex
- Passenger Class
- Age
- AgeGroup
- Fare
- FareGroup
- Embarked
- Title
- Deck
- FamilyType

---

## Multivariate Analysis

Performed:

- Correlation Heatmap
- Pairplot
- Crosstab Heatmaps
- Multi-variable Survival Analysis
- Combined Feature Comparisons

---

# 📌 Key Insights

Some major findings include:

- Female passengers had a significantly higher survival rate than males.
- First Class passengers were more likely to survive than Third Class passengers.
- Children generally had better survival rates than adults.
- Higher ticket fares were associated with higher survival probabilities.
- Passengers embarking from Cherbourg showed the highest survival rate.
- Passenger titles such as **Mrs**, **Miss**, and **Master** had better survival rates than **Mr**.
- Upper deck passengers generally experienced better survival outcomes.
- Small families had better survival rates than passengers traveling alone or in large families.
- Passenger class, gender, fare, title, and deck were the strongest factors associated with survival.

---

# 📂 Repository Structure

```text
titanic-exploratory-data-analysis/
│
├── Titanic Eda.ipynb
├── Titanic Dataset.csv
├── README.md
└── images/
```

---

# 🚀 How to Run

Clone this repository:

```bash
git clone https://github.com/Maganpreet-Singh/titanic-exploratory-data-analysis.git
```

Move into the project directory:

```bash
cd titanic-exploratory-data-analysis
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and run all cells sequentially.

---

# 📚 Learning Outcomes

This project helped strengthen skills in:

- Python Programming
- Pandas
- NumPy
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Matplotlib
- Seaborn
- Statistical Analysis
- Data Visualization
- Insight Generation
- Storytelling with Data

---

# 🔮 Future Improvements

Possible future enhancements include:

- Advanced Feature Engineering
- Statistical Hypothesis Testing
- Missing Value Imputation Strategies
- Machine Learning Models
- Feature Importance Analysis
- Interactive Dashboards

---

# 📄 License

This project is created for **learning**, **practice**, and **portfolio** purposes.

---

# 👨‍💻 Author

**Maganpreet Singh**

GitHub: https://github.com/Maganpreet-Singh

---

⭐ If you found this project helpful, consider giving the repository a **Star** on GitHub!
