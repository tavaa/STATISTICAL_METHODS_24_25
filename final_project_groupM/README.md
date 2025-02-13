# Final Project Group M - Flight Fare Predictions

This project contains the material for the final exam project of the *Statistical Methods* for the academic year 2024-25. This course is offered by UniTS (Università degli Studi di Trieste), Trieste, Italy.

## Table of Contents
- [Introduction](#introduction)
- [Key Points](#key-points)
- [Prerequisites](#prerequisites)
- [Structure](#structure)
- [Usage](#usage)
- [Contributions](#contributions)
- [References](#references)

## Introduction

This **advanced analysis** focuses on a dataset of internal flights, aiming to uncover insights and build predictive models. The study begins with an exploratory data analysis to examine the descriptive characteristics of the dataset, such as distributions, trends, and correlations among key variables like flight duration, departure time, and fare prices. Then, multiple regression techniques will be applied, including *linear regression* to assess linear relationships, *polynomial regression* to capture non-linear patterns, and *random forest models* for robust and flexible predictions. Additional advanced analysis will involve evaluating model performance using metrics such as *AIC*, *BIC*, *RMSE*, *MAE* and *$R^2$*. This comprehensive approach aims to provide actionable insights and accurate models for predicting flight fares and understanding influential factors.

**Goal**: The purpose of this analysis is to predict the quantitative variable *price* (response), focusing on identifying key factors that influence it and building accurate predictive models to estimate flight fares.

## Key Points

* Data Import and Cleaning.
* Explorative Data Analysis.
* Evaluation Metrics
* Linear Regression and Variants: A Comparative Analysis on the Complete Model
* Linear Regression and Variants: A Comparative Analysis on the Splitted Model
* MARS - Multivariate Adaptive Regression Spline.
* Regression Trees, XGBoost and Random Forest approaches
* Results and Conclusions


## Prerequisites

- Python3. (built with python 3.10.0)
- Jupyter environment.
- R studio + R (for MARS).

## Structure

- `data/`: Contains datasets
- `GroupM_analysis_notebook.ipynb`: analysis notebook.
- `GroupM_analysis_notebook_MARS.Rmd`: analysis notebook in R (only for MARS)
- `GroupM_analysis_notebook_MARS.pdf`: Knit of the Rmd.
- `GroupM_analysis_presentation.pdf`: presentation
- `requirements.txt`: Python packages.

## Usage

1. **Clone or Download the Repository**  

   Clone or download it to your local machine.

2. **Create a Virtual Environment for your project**

   ```python
    python3.10 -m venv venv
   ```

   Load the virtual environment:

   - On windows PowerShell: `.\venv\Scripts\activate.ps1`
   - On Linux and Git Bash / macOs: `source venv/bin/activate`

   Deactivate once termined:

   ```python
    deactivate
   ```
   
3. **Install Python Dependencies**

    ```python
    pip install -r requirements.txt
    ```

4. **Run Notebook**

    Run the main notebook, read the presentation or the `GroupM_analysis_notebook_MARS.pdf` pdf knit.

## Contributions

**Authors**

* Ricatti Luca <luca.ricatti@studenti.units.it>
* Tavano Matteo <matteo.tavano@studenti.units.it>
* Valeri Massimiliano <massimiliano.valeri@studenti.units.it>

## References 

1. Flight Fare Prediction Dataset: https://www.kaggle.com/code/varunsaikanuri/flight-fare-prediction-10-ml-models/input
