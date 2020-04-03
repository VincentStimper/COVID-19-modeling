# Modeling the spread of COVID-19

## Model

To model the spread of COVID-19, the very simple and widely used lgoistic function

![Model](https://raw.githubusercontent.com/VincentStimper/COVID-19-modeling/master/equations/model.jpg)

where

![sigmoid](https://raw.githubusercontent.com/VincentStimper/COVID-19-modeling/master/equations/sigmoid.jpg)

The parameters of the model are determined by least square regression using the
[dataset of the Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19).


## Results

The estimate for the total number of cases, deaths, and the mortality for each country are given
[here](https://github.com/VincentStimper/COVID-19-modeling/blob/master/logistic-results.csv). Furthermore,
plots of the regression are available in the `plots` folder. The green line indicates the date of inflection for both the cases and infections.

![Cases Germany](https://raw.githubusercontent.com/VincentStimper/COVID-19-modeling/master/plots/cases_germany.png)

![Deaths Germany](https://raw.githubusercontent.com/VincentStimper/COVID-19-modeling/master/plots/deaths_germany.png)
