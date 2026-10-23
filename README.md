# README:
# Book Catalogue Price Analysis (books.toscrape.com)

End-to-end project: scrape -> clean -> explore -> linear regression -> report.

## Dependencies
- import re, time, warnings
- from pathlib import Path
- from urllib.parse import urljoin
- import requests
- from bs4 import BeautifulSoup
- import numpy as np, pandas as pd
- import matplotlib.pyplot as plt, seaborn as sns
- import statsmodels.api as sm
- from scipy import stats
- from sklearn.model_selection import train_test_split, cross_val_score
- from sklearn.linear_model import LinearRegression, RidgeCV
- from sklearn.metrics import r2_score, mean_absolute_error, mean_squared_error
- from statsmodels.stats.outliers_influence import variance_inflation_factor

## Contents
- book_price_analysis.ipynb
- figures
- report/project_report.docx
- report/model_metrics.csv
- report/coefficients_top15.csv 
- data/raw/books_raw.csv
- data/processed/books_clean.csv

## Re-running
The code does manage to run fully
