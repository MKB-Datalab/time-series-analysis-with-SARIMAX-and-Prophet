# :chart_with_upwards_trend: Time Series Analysis and Forecasting with SARIMAX and Facebook Prophet models: An Intro

![](https://github.com/dpbac/mkb-time-series-tutorial/blob/master/images/aron-visuals-BXOXnQ26B7o-unsplash.jpg)
Photo by <a href="https://unsplash.com/@aronvisuals?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Aron Visuals</a> on <a href="https://unsplash.com/@aronvisuals?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Unsplash</a>
  

This repository presents in three notebooks some basics about time series and introduceS SARIMAX models and Facebook Prophet forecasting algorithm.

In **[01-Intro_time_series_tutorial.ipynb](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/notebooks/01-Intro_time_series_tutorial.ipynb)** you learn about time series properties and how to identify them using both statistical and graphical tools.

Next, in **[02-Forecasting_with_SARIMAX.ipynb](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/notebooks/02-Forecasting_with_SARIMAX.ipynb)** you are introduced to ARIMA models and its variants. There we apply SARIMA model on a [store-item sales data](https://www.kaggle.com/c/demand-forecasting-kernels-only) and forecast the sales 3 months in the future.

In the last notebook, **[03-Forecasting_with_Facebook_Prophet.ipynb ](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/notebooks/03-Forecasting_with_Facebook_Prophet.ipynb)**, we introduce Facebook Prophet. We compare it with other models such as SARIMAX and apply it to the same dataset. We finalize by comparing the performance of all models obtained (SARIMA and Prophet models).

## :file_folder: Data

In the pratical examples we used the following data:

1. Data obtained from [Google Trends](https://trends.google.com/trends/) consisting on how many times the word `diet` was searched in US in the period from the week starting at `2016-03-27` till week starting at `2021-03-21`. This data can be found [here](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/data/raw/time-series/multiTimeline_diet.csv).

2. [global temperature dataset time series](https://datahub.io/core/global-temp#data). This dataset includes global monthly mean temperature anomalies in degrees Celsius from 1880 to the present. Data are included from the GISS Surface Temperature (GISTEMP) analysis and the global component of Climate at a Glance (GCAG). This data can be found [here](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/data/raw/time-series/monthly_csv.csv).

3. Data from Kaggle's competition [**Store Item Demand Forecasting Challenge**](https://www.kaggle.com/c/demand-forecasting-kernels-only) which consists of 5 years of store-item sales data split in a training dataset (train.csv) and a test dataset (test.csv). 

More specifically, in our examples, we used a part of this data that can be found [here](https://github.com/MKB-Datalab/time-series-analysis-with-SARIMAX-and-Prophet/blob/master/data/processed/sales_store_2_item_28.csv).



## :wrench: Tools

- statsmodel
- Prophet

Brief description of the tools used

## :computer: Install requirements
* Install requirements using `pip install -r time_series_requirements.txt`.
  * Make sure you use Python 3.
  * You may want to use a virtual environment for this.

-------------------------------------
[:arrow_backward: **Back to repository main page**](https://github.com/MKB-Datalab/mkbdatalab_knowledge_repository_main)