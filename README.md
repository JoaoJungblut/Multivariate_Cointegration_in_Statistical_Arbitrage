# Multivariate Cointegration in Statistical Arbitrage
This repository houses codes and reports pertaining to my final CQF project. Here, I apply the Johansen approach to construct a cointegrated portfolio.

## Code Structure and Project Report Details

The Jupyter Notebook, TS_JOAORAMOSJUNGBLUT_CODE.ipynb, associated with this project encompasses the developed code, spanning various stages. Initially, it focuses on data loading and manipulation, followed by the implementation of the Johansen class, used for conducting cointegration tests and parameter estimation. The Backtest class is created for portfolio construction and backtest execution, while the Performance class is responsible for calculating risk and return measures, as well as generating graphs and result tables.

The PDF file TS_JOAORAMOSJUNGBLUT_REPORT.pdf, in turn, serves as the final project report, providing a comprehensive exposition. This document covers the models used, details the adopted trading strategy, presents the obtained results, and suggests possible improvements to be implemented in the future.

The provided Excel files, Ibovespa.xlsx, StockPrice.xlsx and MarketComposition.xlsx, constitute the databases for project development, respectively, containing information such as Bovespa index data, adjusted closing prices of stocks, and market composition.

Additionally, there is a CSV file, FF_factors.csv, that stores Fama-French factor data generated in another repository, "BR-Fama-French-Factors". These data are used for conducting robustness tests, expanding the analysis and validation of the proposed model.
