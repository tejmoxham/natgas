
<!--- 
- Rolling train/test set and evaluation.
- Plots forecasting into the future.
- Inclusion of confidence intervals 
- Gravity model use GBP as substitute
- POtential Factors: Temperture, weather
--->

## NatGas Flows

Forecasting the movement of natural gas import/exports flows has become a crucial tool for stakeholders, enabling them to enhance their investment decisions, mitigate potential risks, and optimize resource allocation. With recent socio-economic events significantly affecting the supply of natural gas to the UK and Europe, accurate import/export forecasting can mitigate risks to supply and price volatility.

## Description

This repository contains various project exploring different forecasting models and methodologies of natural gas import/export flows from UK. The main files included are summarised below nb 

- Visualisation of the used datasets and some initial anlysis.
- Basic SARIMA + GARCH model of net montly natural gas imports.
- Gravity trade model of net monthly natural gas imports.

Future developments for projects will look at using higher resolution data on a day/week timeframe as well as the use of AIS data and country of origin for LNG forecasts.

## Python Setup

A python version later than 3.8 is required, the python packages required are included in the `requirements.txt` file and can be installed by running
```
pip install requirements.txt
```
It is recommended that a new environment is generated and used for the project which can be achieved using the `conda create` command. 

## Sources

Historical data is already partly included in the `data` directory and has been adapted from the following publically available sources. Educational resources including articles included in the `resources` directory.

Department for Energy Security and Net Zero (2023) "Natural gas imports and exports (ET 4.3 - monthly)"
https://www.gov.uk/government/statistics/gas-section-4-energy-trends
