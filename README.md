# Introduction to Machine Learning
## How Models Work
Machine Learning Models work by learning patterns from data (**fitting**) and using these patterns to make predictions. The data used to fit a model is called the **training data**.

Models like **Decision Trees** use branching yes or no decisions to make predictions. The deeper the tree, the more accurate the prediction tends to be.

## Basic Data Exploration
Pandas is the most commonly used tool for data manipulation in data science. The main Pandas feature we will work with are DataFrames which are essentially tables, a lot like an Excel sheet.

## Model Validation
One way we can calculate a model's accuracy is by calculating the Mean Absolute Error (MAE)
```
  error = actual - predicted
```
We can use two types of data in model validation:
- **In sample data** - this is where the model is validated using the same data used to train it. This strategy is ineffective because the training data my have patterns that are not representative of real world data. The model will thus learn these patterns and appear accurate in training but will fail with real world data.
- **Validation predictions** - this is where we use data that the model has not seen before to test it.

## Underfitting and Overfitting
**Underfitting** is where the model fails to capture enough patterns to make an accurate prediction. **Overfitting** is where the model captures too many patterns that may only exist in the training data and not actually be reflected in real world data.

The most accurate models strike a balance between underfitting and overfitting.

## Random Forests
These models use multiple decision trees and average out the prediction.
