# Introduction to Time Series Analysis with Applications in R

## Setup

Download and install R: https://www.stats.bris.ac.uk/R/
Download and install: RStudio: https://posit.co/download/rstudio-desktop/

## Day 1: Foundations

### 10:00-10:50 - Analysis with Tidyverse

We will kick off by familiarizing ourselves with the R programming environment. We'll start by exploring RStudio, a powerful IDE for R, and cover the basics of R syntax. We will introduce the tidyverse collection, which will form the backbone of our data analysis workflow throughout the workshop.

#### Key Topics:
- Overview of R and RStudio: Navigating the interface, creating projects, and understanding the environment.
- Essential R Data Structures: Understanding vectors, data frames, and tibbles.
- Getting Hands-On: Simple exercises in data manipulation using  and plotting with  to introduce tidy data concepts.


### 11:00-11:50 - Exploring Time Series Data

We'll introduce time series data and learn how to work with time-indexed data structures using the  package. We will explore how time series data differs from cross-sectional data and cover essential data preparation techniques for time series analysis.

#### Key Topics:
- Introduction to Time Series Data: Understanding temporal structure and common formats.
- Visualizing Time Series: Creating effective time series plots, showcasing trends, seasonality, and potential anomalies.
- Hands-On Activity: Importing a financial dataset, transforming it, and creating exploratory visualizations.


### 12:00-12:50 - Random Walks

We will cover random walks, one of the simplest models for modeling time series. We will use the  package to simulate and visualize random walks, which will help us build an intuition for the nature of financial time series.

#### Key Topics:
- Understanding Random Walks: Introduction to stochastic processes and why they matter in finance.
- Simulating Random Walks in R.
- Hands-On Activity: Generating random walks and visualizing them. We'll also compare random walks to actual financial time series.


### 12:50-14:00 - Lunch Break

### 14:00-14:55 - Stationarity: Pre-Testing

Stationarity is a critical concept in time series analysis. We will discuss what stationarity is, why it matters, and how to test for it. We will also explore ways to transform non-stationary data into a stationary form.

#### Key Topics:
- Defining Stationarity: Weak vs. strong stationarity.
- Identifying Non-Stationarity: Visual inspection and statistical tests (e.g., Augmented Dickey-Fuller test).
- Techniques to Achieve Stationarity: Differencing, detrending, and log transformations.
- Hands-On Activity: Apply differencing and transformations to financial data.


### 15:00-16:00 - ARIMA Modelling

We will dive into ARIMA (AutoRegressive Integrated Moving Average) modeling, one of the most popular methods for time series forecasting. We will use the  package to estimate ARIMA models and assess their fit to historical data.

#### Key Topics:
- Introduction to ARIMA Models: Understanding AR, MA, and ARIMA components.
- Identifying Model Parameters: Using ACF and PACF plots to select appropriate parameters.
- Fitting ARIMA Models in R for model estimation and forecasting.
- Hands-On Activity: Fit an ARIMA model to financial data, generate forecasts, and evaluate model performance.
- Newey-West errors 
- Dynamic model for volatility: GARCH models
- Return squared is process for volatility
- Fitted and values
