
# IntroMLFinal

## Dataset

- **Source:** Kaggle – *[Student Performance Factors](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors/data)*
- **Local copy:** `StudentPerformanceFactors.csv`

## Project Goals

- **Main goal** is get graded during the ML intro course 🙃
- **Minor aim #2** is to identify which features makes the most impact on Student's performance from the df with shapes (6607, 20) and features such 


## Approach

- **Model:** `RandomForestRegressor`
- **Baseline:** Linear Regression (R² ≈ 0.77)
- **Pre-processing & feature engineering:** see the notebook for full details.

## Results

| Metric    | Random Forest |
|-----------|---------------|
| Test RMSE | **2.154**     |
| Test R²   | **0.672**     |

### Top-10 Features by Importance

| Rank | Feature                    | Importance |
|-----:|----------------------------|-----------:|
| 1 | Attendance                 | 0.379 |
| 2 | Hours Studied              | 0.242 |
| 3 | Previous Scores            | 0.086 |
| 4 | Tutoring Sessions          | 0.035 |
| 5 | Parental Involvement       | 0.035 |
| 6 | Access to Resources        | 0.033 |
| 7 | Sleep Hours                | 0.029 |
| 8 | Physical Activity          | 0.027 |
| 9 | Family Income             | 0.018 |
|10 | Parental Education Level   | 0.017 |

> **Observation:** Attendance and Hours Studied together account for more than 60 % of the total feature importance.

## Notebook

Reproduce the full workflow in Google Colab:  
[**Open the notebook**](https://colab.research.google.com/drive/1Eznk6vKoy8wkkduFQbPmLH-CY2b2XnwF?usp=sharing)  
A standalone `.ipynb` file is also included in the repo.

## How to Reproduce

```bash
# clone the repo
git clone https://github.com/<your-handle>/IntroMLFinal.git

# run the notebook or execute training script
python src/train_model.py

#no extra dependencies




MIT Licence - use whoever wants, love. 
