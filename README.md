# Predicting Olympic Medals

A linear regression model that predicts how many medals a country will win at the Olympics.

## Data

teams.csv has one row per country per Olympics. The model uses two columns to predict medals:

- athletes: number of athletes the country sent
- prev_medals: medals won at the previous Olympics

## Steps

1. Load the data and keep the needed columns
2. Check correlations and plot the data
3. Drop rows with missing values
4. Train on years before 2012, test on 2012 and 2016
5. Train a linear regression model
6. Evaluate with mean absolute error

## Result

Mean absolute error on the test set: 3.3 medals.

## Run

```
pip install -r requirements.txt
jupyter notebook olympic_medals.ipynb
```

## Credits

Dataset and project idea from Dataquest: https://www.youtube.com/watch?v=Hr06nSA-qww
