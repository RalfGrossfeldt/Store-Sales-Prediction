# [Store-Sales-Prediction](https://www.kaggle.com/competitions/store-sales-time-series-forecasting)
#### Project for predicting Ecuadorian Store sales using time-series data and machine learning algorithms.

**Authors:** Andreas Närep, Ralf Grossfeldt

## Goal of the project

* **Develop different models** for predicting store sales and finding the best possible model we can come up with.
* Learn about **data preparation** for machine learning.
* Learn how to use **time-series data in machine learning**.
* How to **evaluate and compare models**.


## Repository contents

### Data

All of the data, except submission data, is located at `./data/`. **Submission data** is at the root of the project. The data folder in Github is empty since some of the files were too large for pushing and for simplicity no other methods were used for working with large files (e.g. Git LFS). Information about the data and all of the datasets can be found and downloaded at this **[link](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data)**.

### Jupyter Notebook

#### Install

Since **sklearn**, **lightgbm**, **xgboost**, **plotnine** and **pandas** are used, then the following packages need to be installed.

`pip install scikit-learn lightgbm xgboost plotnine pandas`

Or if using conda, then

`conda install scikit-learn lightgbm xgboost plotnine pandas`

#### Usage

For creating the models, doing data preparation and creating a submission file:
* Download datasets from the Kaggle competition.
* Add the downloaded datasets to the `./data/` folder.
* Run all of the notebook cells.
