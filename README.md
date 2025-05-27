# Titanic Dataset - Exploratory Data Analysis (EDA)

## Task 2 for AI & ML Internship

### Project Overview
This project performs comprehensive exploratory data analysis on the Titanic dataset to understand factors that influenced passenger survival.

### Dataset
The Titanic dataset contains information about 887 passengers including:
- Survival status
- Passenger class
- Name, Sex, Age
- Number of siblings/spouses aboard
- Number of parents/children aboard
- Ticket number
- Fare
- Cabin number
- Port of embarkation

### Key Findings
1. Overall survival rate was 38.4%
2. Significant differences in survival by passenger class:
   - 1st class: 62.6%
   - 2nd class: 47.3%
   - 3rd class: 24.2%
3. Female passengers had much higher survival rate (74.2%) than males (18.9%)
4. Passengers who paid higher fares had better survival chances
5. Those traveling alone had slightly lower survival rates than those with family

### How to Run
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Open and run the Jupyter notebook: `notebooks/titanic_eda.ipynb`

### Dependencies
- Python 3.6+
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
