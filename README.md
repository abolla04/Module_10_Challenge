# Module_10_Challenge

This is a Python application that uses Pandas in a Jupyter notebook. It utilizes unsupervised learning to cluster cryptocurrencies by their performance over various timeframes.  The results are displayed on graphs to create visuals of their performance.  

The data is provided in the Resources folder in a csv formatted file.  KMeans is utilized along with an elbow curve to identify the best value for k. Principal Component Analysis is used to show the optimal clusters on scatter plots by using hvPlot.

---

## Technologies

This application leverages Python 3.7 along with the following:

*Pandas
*hvplot
*KMeans
*PCA
*StandardScaler

## Installation Guide

To run the application, install the following libraries and dependencies:

'''python
  import pandas as pd
  import hvplot.pandas
  from path import Path
  from sklearn.cluster import KMeans
  from sklearn.decomposition import PCA
  from sklearn.preprocessing import StandardScaler
'''

---

## Usage

To use this application, clone the repository and run the **crypto_investments.ipynb**

---

## Contributors

Brought to you by ABolla

---

## License

MIT

---