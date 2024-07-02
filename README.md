# SMS Spam Classifier

This project is an SMS spam classifier built using machine learning techniques. The classifier is capable of identifying whether an SMS message is spam or not.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Introduction
The SMS Spam Classifier project aims to help identify and filter out spam messages from legitimate ones using natural language processing (NLP) and machine learning. The project uses a dataset of labeled SMS messages to train a model that can predict the likelihood of a message being spam.

## Features
- Preprocessing of SMS messages (e.g., tokenization, stemming, removing stop words)
- Training various machine learning models
- Evaluating model performance
- Predicting the label of new SMS messages
- Feature extraction using TF-IDF

## Installation
To run the project, ensure you have Python installed. Follow the steps below to set up the environment:

1. Clone the repository:
    ```bash
    https://github.com/Jeetkavaiya/SMS-Spam-Classifier.git
    cd sms-spam-classifier
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```
## Dataset
The dataset used in this project consists of labeled SMS messages indicating whether each message is spam or not. You can download the dataset from [here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

## Model
The classifier uses machine learning models such as Naive Bayes, Support Vector Machines, or any other suitable algorithm. The `train.py` script handles the training process.

## Results
After training, the model is evaluated using various metrics like accuracy, precision, recall, and F1-score.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request


## Acknowledgements
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/) for the SMS Spam Collection dataset.


