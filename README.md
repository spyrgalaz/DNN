
# Spyros_Portfolio

## Data Science in Metallurgy and Mineral Processing
* Data Preprocessing
* Exploratory Analysis of Data Parameters
* Decision Tree with Scikit-Learn
* Building Data Pipeline with TensorFlow

### Using Deep Neural Network to predict Loss of Ignition (LOI) in Rotary Kiln with TensorFlow 
  Loss of Ignition along with reactivity are  critical parameters which control how fast a material reacts in a range of applications.
  In this project a tool is developed in order to  predict LOI. Chemical Composition, Consumptions of P.C. - lpg and Feed Rate were selected as input parameters. TensorFlow with TensorBoard are used.  
 
 Tensorboard graphic model
 
![image](https://user-images.githubusercontent.com/56194024/111066076-d6142400-84c5-11eb-8a63-cd99092393b3.png) 

<table>
  <tr>
     <td>Joint Distributions with seaborn</td>
     <td>Train/Test Loss vs Epochs, MAE vs Epochs</td>
     <td>Exploratory Analysis with seaborn</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/56194024/111068834-0c0bd500-84d3-11eb-9934-07064c8e5073.png" width="350"></td>
    <td><img src="https://user-images.githubusercontent.com/56194024/111068596-1c6f8000-84d2-11eb-9b9c-fe66378b4db9.png" width="350"/></td>
    <td><img src="https://user-images.githubusercontent.com/56194024/111068890-41182780-84d3-11eb-915b-8ca6a3ba667d.png" width="350"/></td>
  </tr>
 </table>

## Timeseries Analysis 
* Data Preprocessing with Pandas
* Building SARIMA model with pdarima
* Building Data Pipeline with TensorFlow tf.data

### Predictive Model for Software Failure using LSTM  and Comparison with SARIMA
This problem comprised of a single series of observations and model is required to learn from the series of past observations to predict the next value in the sequence.
The model demonstrates better outcames from the classical autoreggressive models like Arima and Simple Dense Neural Networks.SARIMA model results are given in order to understand the differences between them.

<table>
  <tr>
     <td>Graphical Summary</td>
     <td>Sarima</td>
     <td>LSTM</td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/56194024/111117853-bf76d700-8570-11eb-8f8b-1f2153f56538.png" width="350"></td>
    <td><img src="https://user-images.githubusercontent.com/56194024/111118042-f5b45680-8570-11eb-9ea9-bb00fd4b417a.png" width="350"/></td>
    <td><img src="https://user-images.githubusercontent.com/56194024/111118248-314f2080-8571-11eb-90e7-245e9f57fa8c.png" width="350"/></td>
  </tr>
 </table>

## Linear Regression Analysis for Flight Delays with PySpark in Google-Colab
* Run spark in Colab-install the dependencies
* Data Preprocessing with pyspark.ml 
* Building Data Pipeline for Linear regression in order to predict delays in airports from multiple features

<img src='https://user-images.githubusercontent.com/56194024/111155106-ae43bf80-859c-11eb-8fd3-677870785aaf.png' width="270">

## Automated Machine Learning workflow using genetic algorithms with TPOT and scikit learn

TPOT is an open-source library that automate the most tedious part of machine learning by intelligently exploring thousands of possible pipelines to find the best one for your data.
The dataset involves predicting whether sonar returns indicate a rock or simulated mine.
Test harness of repeated stratified 10-fold-cross-validation is used.

!<img src='https://user-images.githubusercontent.com/56194024/112471510-ac37e880-8d74-11eb-8f49-d392414d206d.png' width="270">

## Bitcoin Web Scraping with Beautiful Soup on Colab

Heatmap for feature extraction.

<img src='https://user-images.githubusercontent.com/56194024/112744758-86e0ef80-8fab-11eb-8ee1-c5e9be8d1256.png' width="270">


## What Is the Sharpe Ratio?
The Sharpe ratio was developed by Nobel laureate William F. Sharpe and is used to help investors understand the return of an investment compared to its risk. The ratio is the average return earned in excess of the risk-free rate per unit of volatility or total risk. Volatility is a measure of the price fluctuations of an asset or portfolio.

The Sharpe ratio is usually calculated for a portfolio and uses the risk-free interest rate as benchmark. We will simplify our example and use stocks instead of a portfolio. We will also use a stock index as benchmark rather than the risk-free interest rate because both are readily available at daily frequencies and we do not have to get into converting interest rates from annual to daily frequency.
