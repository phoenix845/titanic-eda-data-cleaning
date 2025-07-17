🚢 Titanic Survival Analysis — EDA & Data Cleaning

This project focuses on data cleaning, handling missing values, and performing exploratory data analysis (EDA) on the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data). The goal is to uncover patterns that influenced survival and visualize them using Python tools.


📁 Project Structure

Task_02_EDA_Titanic/
├── titanic_eda.ipynb 
├── README.md 
├── output_report.pdf 
└── dataset/
└── train.csv 

🔧 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook


📊 Steps Performed
1. 🔍 Data Loading & Exploration
- Loaded `train.csv` using Pandas
- Displayed basic information, shape, and column types
- Identified missing values and outliers

2. 🧼 Data Cleaning
- **Handled Missing Values**:
  - `Age`: filled with median
  - `Embarked`: filled with mode
  - `Cabin`: dropped (too many missing values)
- **Removed Outliers**:
  - Capped extreme `Fare` values at the 99th percentile
- **Converted Categorical to Numerical**:
  - `Sex`: mapped to 0 and 1
  - `Embarked`: used one-hot encoding (`get_dummies`)

3. 📈 Exploratory Data Analysis (EDA)
- **Visualized survival counts** overall and by key features:
  - `Sex` vs `Survived`
  - `Pclass` vs `Survived`
  - `Age` distribution
  - `Fare` distribution vs `Survived`
- **Added legends, labels, and titles** to all visualizations


🔍 Key Insights

- **Females had a higher survival rate** than males.
- **1st class passengers** had a better chance of survival.
- **Children and younger passengers** were more likely to survive.
- Passengers who **paid higher fares** had slightly higher survival odds.


📂 How to Run

1. Clone the repository or download the project folder.
2. Install required libraries (if not already installed):
   ```bash
   pip install pandas numpy matplotlib seaborn


🔧 Tools & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook / Google Colab


 📊 Steps Performed

1. 🔍 Data Loading & Exploration
- Loaded `train.csv` using Pandas
- Displayed basic information, shape, and column types
- Identified missing values and outliers

2. 🧼 Data Cleaning
- **Handled Missing Values**:
  - `Age`: filled with median
  - `Embarked`: filled with mode
  - `Cabin`: dropped (too many missing values)
- **Removed Outliers**:
  - Capped extreme `Fare` values at the 99th percentile
- **Converted Categorical to Numerical**:
  - `Sex`: mapped to 0 and 1
  - `Embarked`: used one-hot encoding (`get_dummies`)

3. 📈 Exploratory Data Analysis (EDA)
- **Visualized survival counts** overall and by key features:
  - `Sex` vs `Survived`
  - `Pclass` vs `Survived`
  - `Age` distribution
  - `Fare` distribution vs `Survived`
- **Added legends, labels, and titles** to all visualizations


🔍 Key Insights

- **Females had a higher survival rate** than males.
- **1st class passengers** had a better chance of survival.
- **Children and younger passengers** were more likely to survive.
- Passengers who **paid higher fares** had slightly higher survival odds.


📂 How to Run

1. Clone the repository or download the project folder.
2. Install required libraries (if not already installed):
   ```bash
   pip install pandas numpy matplotlib seaborn
