# Introduction

This repository contains my solution to the Grab  AI for S.E.A. [Safety Challenge](https://www.aiforsea.com/safety).

# Prerequisites

The [notebooks](/notebooks) were developed on Databricks using Python 3 and PySpark running on the  5.4 ML
Beta (includes Apache Spark 2.4.0, Scala 2.11) runtime.

# Usage

Execute the notebooks in the following order and modify any directory and file names accordingly:
* [01_data.ipynb](/notebooks/01_data.ipynb): This notebook downloads the dataset and saves it in parquet format
* [02_EDA.ipynb](/notebooks/02_EDA.ipynb): This notebook does some exploratory data analysis and removes outliers
* [03_feature_engineering.ipynb](/notebooks/03_feature_engineering.ipynb): This notebook computes features that will be used to build
models to classify a trip
* [04_modelling.ipynb](/notebooks/04_modelling.ipynb): This notebook builds and validates a few models
* [05_evaluation.ipynb](/notebooks/05_evaluation.ipynb): This notebook is meant to evaluate the best model found in the previous
notebook against the hold-out dataset.

More details are available in each notebook.

