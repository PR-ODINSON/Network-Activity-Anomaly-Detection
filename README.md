# Network Attack Detection with Random Forest Classifier
## Overview
This repository contains code for detecting network attacks using a Random Forest Classifier. The model is trained on a dataset with features such as protocol type, service, flag, and various traffic statistics. After preprocessing and encoding categorical variables, the model achieved impressive performance on the validation set.

## Project Structure
data/: Contains the training and test datasets (e.g., train_data.csv, test_data.csv).
notebooks/: Jupyter notebooks used for data exploration, preprocessing, and model training.
src/: Python scripts for model training and evaluation.
submission.csv: Predictions on the test dataset formatted for evaluation.
## Getting Started
### Clone this repository to your local machine.
Install the required dependencies (e.g., pandas, scikit-learn).
Run the training script (train.py) to train the Random Forest Classifier.
Evaluate the model’s performance using the validation set.
Make predictions on the test dataset and create the submission file.
## Usage
Modify the hyperparameters in train.py to fine-tune the model.
Explore the Jupyter notebooks in notebooks/ for detailed analysis.
Feel free to contribute or extend the project!
