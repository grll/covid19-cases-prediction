# Predicting COVID-19 cases in Switzerland

This repository contains 2 notebooks presenting cumulative covid-19 cases prediction in Switzerland:

- `ExploratoryDataAnalysis.ipynb` contains a brief EDA and a first attempt at performing a Poisson Regression on the data.
- `CasesPrediction.ipynb` fit different exponential and other common growth models to the data.

The `CasesPrediction.ipynb` heavily use the package `growth_modeling` wich is 
also part of this repository. In this package several growth model are implemented
and a simple API similar to sklearn is exposed for easy usage. 

A documentation for the `growth_modeling` package is available [here](https://growthmodeling.netlify.com/).
