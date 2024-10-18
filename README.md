# A Memory Guided Transformer for Time Series Forecasting

This is the original pytorch implementation of Memformer in the following paper: A Memory Guided Transformer for Time Series Forecasting.

## Requirements

- Python 3.6
- See `requirements.txt`

## Data Preparation

Memformer is implemented on several public multivariate time series datasets.

- **Weather:** Weather data, published by a weather station in Jena Germany, recording meteorological data throughout one year at a sampling frequency of once per 10 minutes. You can download the data from the link: [https://www.bgc-jena.mpg.de/wetter/](https://www.bgc-jena.mpg.de/wetter/).
- **Traffic:** Traffic data, published by the California Department of Transportation, capturing congestion data from the San Francisco Bay area freeways through multiple sensors at different locations. This dataset has a sampling frequency of once per hour and covers 48 months. You can download the data from the link: [https://github.com/zhouhaoyi/ETDataset](https://pems.dot.ca.gov/).
- **Electricity:** Electricity data, published by the University of California Irvine Machine Learning Repository, recording the electricity consumption of 370 users between 2011 and 2014, with a sampling frequency of once per 15 minutes. You can download the data from the link: [https://zenodo.org/record/4656132#.Y3ttxezMIeY](https://archive.ics.uci.edu/dataset/321/electricityloaddiagrams20112014).
- **ETT:** ETT data comprising four datasets: ETTh1, ETTh2, ETTm1, and ETTm2, which record the oil temperature and other associated variables of electricity transformers. These datasets span two years, with ETTh1 and ETTh2 being sampled once per hour and ETTm1 and ETTm2 being sampled once every 15 minutes. You can download the data from the link: https://github.com/zhouhaoyi/ETDataset.
  
## Running Example
	sh ./scripts/Memformer/etth2.sh

## Results
-  See result.txt
