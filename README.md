# Streamlit
#### This repository contains all my works done on Streamlit, a platform which turns data scripts into shareable web apps in minutes.

### References
- Data Professor ([Link to YouTube channel](https://www.youtube.com/channel/UCV8e2g4IWQqK71bbzGDEI4Q))

### Table of Contents
- [Multiclass Clasification](#multiclass-classification)
  - [Iris Flower Classification](#iris-flower-classification)
  - [Penguins Species Classification](#penguins-species-classification)
- [Visualization](#visualization)
  - [Static Stock Price Visualization](#static-stock-price-visualization)

# Multiclass Classification
### [Iris Flower Classification](https://github.com/Hongyanlee0614/Streamlit/tree/main/Iris%20Flower%20Classification)
Using sklearn's build-in iris flower dataset, train a random forest model to perform on multi-classificatio task, that is to predict the species of flower (either setosa, versicolor or virginica) based on user inputs on 4 parameters (sepal length, sepal width, petal length and petal width).

### [Penguins Species Classification](https://github.com/Hongyanlee0614/penguins-classification)
Build a random forest model for predicting penguins species and save into a pickle file. Then, read in the pickle file and predict penguins species based on user input (slider or file uploading).
View the deployed website [here](https://hy-penguins-classification.herokuapp.com/).

# Visualization
### [Static Stock Price Visualization](https://github.com/Hongyanlee0614/Streamlit/tree/main/Static%20Stock%20Price%20Visualization)
Using yfinance module, obtain the stock price data of Google from 31 May 2010 to 31 May 2021. Then, visualize it using streamlit's line_chart function.
