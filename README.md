# Machine-Leaning-Pipeline-From-Scratch

Build complete ML Algorithms and Pipelines

## 1- Data Exploration

I use [Pima Indian Diabetes Dataset](https://www.kaggle.com/datasets/kumargh/pimaindiansdiabetescsv) in this project. 

In this file, first open CSV file with different methods such as Numpy, Pandas. 

Then check data dimension, type of attributes, summary, class distribution, pairwise pearson correlation, skew of each attribute and info. 

## 2- Data Visualization

Visualize data using matplotlib.

Histogram, Density Plots, Box and Whisker Plots, Correlation Matrix Plot, Scatterplot Matrix.

## 3- Data Preparation

Prepare data before performing any ML algorithms on it. 

The data is usually not ready to be used in a ML model, therefore preparing it is important. 

There are multiple methods such as Rescaling, Standardization, Normalization, Binarization to prepare the data for a ML model and should choose depending on the model you want to use. 

## 4- Feature Selection

The data features that are used to train ML models have a big influence on the performance of the model. 

Irrelevant or partially relevant features can negatively impact model performance. 

Feature selection or feature extraction is a process where we automatically select those features in the data that contribute most to the prediction variable. 

Three main benefits of selecting informative feature before modelling are:

• Reduces Overfitting: Less redundant data means less opportunity to make decisions based on noise.

• Improves Accuracy: Less misleading data means modelling accuracy improves.

• Reduces Training Time: Less data means that algorithms train faster.

Here I used Chi-squared, Recursive Feature Elemination and PCA as feature selection methods. 

Bagged decision trees like Random Forest and Extra Trees can be used to estimate the importance of features.

## 5- Resampling

Resampling means splitting your data into test/validation/train datasets. 

Using all the data to train the algorithm, the algorithms will not perform well on the unseen data in most cases. (Overfitting)

The best way to evaluate the performance of an algorithm would be to make predictions for new data to which we already know the answers. 

But what if we do not have data with answers? 

In this case, we use resampling methods that allow us to make accurate estimates for how well our algorithm will perform on new data. 

There are many methods to split the data into training and testing datasets. 

Here I use the following methods:

• Train and Test Sets

• k-fold Cross-Validation

• Leave One Out Cross-Validation

• Repeated Random Test-Train Splits


