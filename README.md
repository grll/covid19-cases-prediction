# Predicting COVID-19 cases in Switzerland

This repository contains 2 notebooks presenting an attempt and findings into
fitting growth models to covid-19 cumulative cases in Switzerland:

- `ExploratoryDataAnalysis.ipynb` presents a brief EDA, and presents a first attempt at performing a Poisson Regression on the data.
- `CasesPrediction.ipynb` fit different exponential and other common growth models to the data.

The `CasesPrediction.ipynb` heavily use the package `growth_modeling` wich is 
also part of this repository. In this package several growth model are implemented
and a simple API similar to sklearn is exposed for easy usage. 