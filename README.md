
# Spyros_Portfolio

## Data Science in Metallurgy and Mineral Processing
* Data Preprocessing
* Exploratory Analysis of Data Parameters
* Decision Tree with Scikit-Learn
* Building Data Pipeline with TensorFlow

### Using Deep Neural Network to predict Loss of Ignition (LOI) in Rotary Kiln with TensorFlow 
  Loss of Ignition along with reactivity are a critical parameters which control how fast a material reacts in a range of applications.
  In this project a tool is developed in order to  predict LOI as output  from Chemical Composition, Fuel Consumptions of P.C., lpg and Feed Rate as inputs.TensorFlow with TensorBoard are used.  
 
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
The model demonstrates better outcames from the classical autoreggressive model like Arima and Simple Dense Neural Networks.SARIMA model results are given in order to understand the differences between them.

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

## Regression Analysis with PySpark
* Run spark in Colab-install the dependencies
* Data Preprocessing with pyspark.ml 
* Building Data Pipeline for Linear regression in order to predict delays in airports from multiple features
