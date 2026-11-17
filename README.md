# California-Electricity-Demand
## Time-series Forecasting on California Electricity Demands
** ### Nessa Jafari, Guillermo Valencia, and Brian Paulotzky **

## Background
California's electricity demand is projected to more than double between 2020 and 2050 as buildings and vehicles switch from gas to electricity. Our project forecasts that demand using the Sup3rLoad dataset, a U.S. Department of Energy dataset produced by Evolved Energy Research.
Sup3rLoad models final energy demand for every state by sector, subsector, technology, and fuel, under a Central and a Reference scenario, in mmBtu. We use the Central scenario for California, summed across all sectors for electricity only and converted to terawatt-hours (TWh), giving one yearly series from 2020 to 2050 (31 observations). Our team compares three model families on this series: ARIMA, exponential smoothing (ETS), and time series linear regression (TSLM).

## Literature Review and Forecasting Methods
Electricity demand forecasting is an important aspect in determining future energy needs and preparing for changes in usage. As more homes and companies switch to electric vehicles, heaters and appliances, the need for reliable electricity estimates continues to grow. Historical energy data may be used to analyze trends in use, and to estimate future trends of demand. These projections can also inform decisions on energy resources, infrastructure, and long-term planning, particularly for states like California that are rising power use across several industries.

## Comparison of Forecasting Models
A number of statistics can anticipate power usage in the future. In this project we will focus on ARIMA, Exponential Smoothing (ETS) and Time Series Linear Regression (TSLM). All three strategies try to find patterns in previous data, but they employ different techniques to make forecasts. ARIMA looks at relationships in historical observations. ETS looks at changes in the level and trend of the data. TSLM uses regression to estimate changes in power demand over time. We can compare both strategies side-by-side to gain insight into which methodology is better suited to project California’s long-term electricity needs.

## Model Evaluation and Project Objectives
Consistency is needed so that the outcomes of each forecasting model can be compared equitably. In our project, we use the identical annual California electricity demand series for all three models. The data from 2020 through 2044 is used as the training period while the data from 2045 through 2050 is saved for testing. To test the accuracy of the forecast, we will use RMSE, MAE, and MAPE to evaluate how near the projected values are to the actual observations . Our team will use the same data and evaluation criteria for each method to evaluate which model can best and most reliably anticipate California’s electricity demand until 2050.

## Findings
Overall, the team came to some different conclusions based upon the models that were used, TSLM, ETS, and ARIMA. For one of the three models, Log-linear TSLM, the power trends were downward from 2020 to around 2045 then heading back upwards between 2045 and 2055. The last models, ETS and ARIMA, the trends seemed to be going upwards for energy consumption forecasts as the years went on towards 2055. More analysis will have to be completed to better understand the differences in these conclusions and possibly different choices of models will be made as we get closer to the final drafts.

The Log-linear TSLM performed best for TSLM models at an AICc of -229 and the ARIMA had an RMSE of 4.7 TwH thus getting extremely close to nominal values for errors.

