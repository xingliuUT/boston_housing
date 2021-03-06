# Machine Learning Engineer Nanodegree
## Project: Predicting Boston Housing Prices

### Code

The code is in the `boston_housing.ipynb` notebook file. Visualization code is in `visuals.py` Python file.  The `housing.csv` dataset file contains data for this project.

### Run

```bash
jupyter notebook boston_housing.ipynb
```

### Data

The modified Boston housing dataset consists of 489 data points, with each datapoint having 3 features. This dataset is a modified version of the Boston Housing dataset found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Housing).

**Features**

1. `RM`: average number of rooms per dwelling
2. `LSTAT`: percentage of population considered lower status
3. `PTRATIO`: pupil-teacher ratio by town

**Target Variable**

4. `MEDV`: median value of owner-occupied homes

### Conclustion

The decision tree model with a maximum depth of 4 chosen by cross validation is applied to the data. However, I don't find the model very useful for several reasons, including the robustness of the model, relavancy of the predictors, as well as the time and location where the data was collected.
