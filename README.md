# State-level Aid's Impact on the Proportion of Student Debt

## Overview
This project analyzes how state-level financial aid impacts the proportion of students taking on federal student debt and the median debt at graduation, using logistic regression on institutional and state-level data (2019–2023).

## Table of Contents
- [Overview](#overview)
- [Data](#data)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Data
Three primary sources of data were utilized and merged 
1. U.S. Department of Education College Scorecard (Scorecard) – includes information on the average student loan debt at graduation (Dependent variable), proportion of students who take on debt (Dependent variable) and Institutional demographics, Private vs public university indicator, etc. 
2. Integrated Postsecondary Education Data System (IPEDS) – includes State/local government grant data and additional tuition programs information 
3. State Higher Education Executive Officers Association (SHEF) – includes state level appropriation data and additional state support and aid metrics 


## Project Structure
```
.
├── data/
│   └── merged_scorecard_shef_and_ipeds.csv
├── Logistic_Regression.ipynb
├── README.md
├── requirements.txt
```

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/log-regression-student-debt-predictor.git
   ```
2. Install dependencies (Python 3.8+ recommended):
   ```sh
   pip install -r requirements.txt
   ```
   Or manually install:
   ```sh
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

## Usage
Open `Logistic_Regression.ipynb` in Jupyter or VS Code and run the cells sequentially. The notebook covers:
- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Logistic regression modeling
- Model evaluation

## Results
- Key predictors of student debt proportions identified.
- Cross-validated classification error reported.
- See notebook for plots and detailed findings.

## License
MIT License.