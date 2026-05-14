# Linear Regression Model — Typing Practice vs. Typing Speed

A simple linear regression model built with scikit-learn that explores the relationship between weekly typing practice hours and typing speed (WPM).

## Dataset

**File:** `typing_speed_dataset.csv`  
**Rows:** 60  
**Independent Variable:** Weekly Practice Hours (hours/week)  
**Dependent Variable:** Typing Speed (words per minute / WPM)

Data was generated to simulate a realistic positive correlation between time spent practicing typing and the resulting typing speed.

## Model Results

| Metric | Value |
|---|---|
| Slope | 4.06 WPM per hour/week |
| Intercept | 21.39 WPM |
| R² Score | 0.97 |
| Mean Squared Error | 16.65 |

**Equation:** `Typing Speed = 4.06 × Practice Hours + 21.39`

The model explains **97%** of the variance in typing speed, indicating a very strong linear relationship between practice hours and typing speed.

## Files

- `typing_speed_dataset.csv` — raw dataset
- `Linear_Regression_Typing_Speed.ipynb` — Google Colab notebook with full model

## Tools Used

- Python 3
- pandas
- NumPy
- scikit-learn
- matplotlib
