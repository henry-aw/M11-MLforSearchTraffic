# *Module 11 Challenge*
## Using Machine Learning to Predict Search Traffic for Better Stock Trading

**Welcome to my Module 11 Challenge repository. Here, you can check out the Supervised Learning approach I took to find out if the ability to predict search traffic can translate into the ability of successfully trading the stock.**

---

## Background
In a bid to drive revenue, I've produced a Jupyter notebook that contains my data preparation, analysis, and visualizations for all the time series data that the company needs to understand. I used text and comments to document my findings.

This is divided into the following sections:
- Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.
- An evaluation of how the company’s stock price correlates to its Google Search traffic.
- A Prophet forecast model that can predict hourly user search traffic.
- Documentation of analysis/findings in comments.
- (Optional) A plot of a forecast for the company’s future revenue

---

## Technologies & Usage
This project leverages scikit-learn, Python 3.7, and the Pandas library with the following requirements and dependencies:
- import pandas as pd
- import hvplot.pandas
- from path import Path
- from sklearn.cluster import KMeans
- from sklearn.decomposition import PCA
- from sklearn.preprocessing import StandardScaler
