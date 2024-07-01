# Sentiment Analysis for Twitter
## Overview
This project focuses on sentiment analysis of Twitter data using neural networks. The pipeline involves data exploration, preprocessing, model construction, training, evaluation, and deployment.
## Project Structure
### Data Exploration and Preprocessing:

* Generate sub-datasets for faster testing and re-index for easier column additions.
* Check data balance and patterns in missing rows using pandas configuration.
* Basic visualization to understand data statistics and sample points.
### Automated Data Exploration:

* Use pandas-profiling for automated data discovery to gain an overview of the dataset.
### Checking Output Category Balance:

* Ensure balance in sentiment categories to avoid biased model predictions.
### Text Preprocessing:

* Convert sentiment labels to indices for model understanding.
### Clean Tweet text by removing stop words and performing lemmatization.
* Tokenize text to prepare it for neural network input.
### Feature Engineering:

* Encode text features using techniques like bag-of-words for model input.
### Model Preparation:

* Remove unnecessary columns (e.g., Tweet Content) and split data into training and test sets.
* Ensure the test set remains untouched to simulate real-world data conditions.
### Model Construction and Training:

* Define a neural network model with embedding layers, bidirectional LSTMs, and dense layers with softmax activation for sentiment prediction.
* Train the model using backpropagation over multiple epochs to optimize accuracy.
### Model Evaluation and Deployment:

* Evaluate model performance using confusion matrices to analyze prediction accuracies across different sentiment classes.
* Refine model based on evaluation results and deploy it for prediction on unseen data.
