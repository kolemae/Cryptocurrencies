# Cryptocurrencies
Using Python and SciKitLearn to cluster and showcase cryptocurrencies on the trading market.

## Table of contents
* [Overview of Cryptocurrencies Project](#overview-of-cryptocurrencies-project)
* [Results](#results)
* [Summary](#summary)

### Resources
- Data Source: crypto_data.csv
- Tools: Python 3.7.13, Jupyter Notebook

## Overview of Cryptocurrencies Project
My client, Accountabilty Accounting, wanted to offer a new cryptocurrency investment portfolio to their customers. I applied unsupervised machine learning to create a report that includes cryptocurrencies on the trading market that could be grouped and classified into a system for investments.

## Results
- I cleaned the original dataframe of 1252 rows to 532 rows
- Used KMeans algorithm to create an elbow curve

![elbow](/Images/elbow.png)

- Applied PCA
- Made a 3D scatterplot to visualize tradable cryptocurrencies

![3D](/Images/3D.png)

- There were 532 tradable cryptocurrencies

![table](/Images/table.png)

- Created a scatterplot of tradable cryptocurrencies using TotalCoinsMined and TotalCoinsSupply

![scatter](/Images/scatter.png)

## Summary
I ended up with two visualizations and a table that makes it easier for my client to show cryptocurrencies to their customers for investment purposes.
