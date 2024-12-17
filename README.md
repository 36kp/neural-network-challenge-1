# Neural Network Challenge

## About
This program is developed to demonstrate my learnings as a part of AI Boot-camp by University of Pennsylvania, Liberal and Professional Studies. [More Info...](https://bootcamp.sas.upenn.edu/artificial-intelligence/landing/)
<br/><br/>
This program puts the topics discussed in **Neural Networks and Deep Learning - Part 1** into action.

## Topics covered in this program
1. **Data Preparation**:
    - Checking data distribution by `value_counts()` on target column
    - Splitting datasets using `train_test_split()` function

2. **Data Normalization**:
    - Identifying scale differences by observing dataframe
    - Using `MinMaxScaler` to normalize features data

3. **Building Neural Network Model**:
    - Creating model using `Sequential` class from Keras
    - Adding layers using `Dense` class
    - Compiling model using `compile()` method
    - Fitting training data using `fit()` method
    - Predicting test values using `predict()` method
    - Evaluating model using `evaluate()` method
4. **Model export and import**:
    - Save model using `.keras` format. (Current models are saved in `saved_models` folder)
    - Load pre-trained models in `.keras` format.
5. **Analyzing Model Performance**:
    - Reviewing and comparing **training accuracy**
    - Reviewing and comparing **testing accuracy**
    - Identifying **Overfitting** and **Underfitting**
    - Interpreting loss and accuracy plots

## How to run this program
Follow instructions below to run this program
> NOTE: Following setup and commands are tested in macOS Sonoma 14.5 only

### Pre-requisites
- **Anaconda** (recommended for environment management)
- **Homebrew** (for installing dependencies)
- Python 3.x
- Pandas library
- TensorFlow library
- Keras library

Install Anaconda and set up your environment:

```bash
# Install Anaconda using Homebrew
brew install --cask anaconda

# Create a new environment (optional but recommended)
conda create -n dev python=3.10

# Activate the environment
conda activate dev

# Install necessary libraries
conda install pandas
conda install -c conda-forge tensorflow
conda install -c conda-forge keras
```

## Usage
- Checkout git repository using git clone
`git clone https://github.com/36kp/neural-network-challenge-1.git`
- Go to the repo home directory
`cd \YOUR_PATH\neural-network-challenge-1`
- Execute the Jupyter Notebook
`jupyter notebook`
- Open `student_loans_with_deep_learning.ipynb` from browser