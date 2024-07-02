# SMS-Spam-Classifier
SMS Classifier is a Complete Model that can detect whether the message is "Spam" or "Not Spam"
<br/>
An end-to-end code for SMS Classifier
<br/>
Dataset - https://www.kaggle.com/
<br/>
Technologies Used, 
    <br/>
    Programming Language: Python
    <br/>
    Natural Language Processing Libraries: NLTK
    <br/>
    Machine Learning Frameworks: SciKit-Learn
    <br/>
    Feature Extraction: TF-IDF
    <br/>
    Classification Algorithms: Naive Bayes, SVM
    <br/>

# SMS Spam Classifier

This project is an SMS spam classifier built using machine learning techniques. The classifier is capable of identifying whether an SMS message is spam or not.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
The SMS Spam Classifier project aims to help identify and filter out spam messages from legitimate ones using natural language processing (NLP) and machine learning. The project uses a dataset of labeled SMS messages to train a model that can predict the likelihood of a message being spam.

## Features
- Preprocessing of SMS messages (e.g., tokenization, stemming, removing stop words)
- Training various machine learning models
- Evaluating model performance
- Predicting the label of new SMS messages

## Installation
To run the project, ensure you have Python installed. Follow the steps below to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sms-spam-classifier.git
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

## Usage
Follow these steps to use the SMS spam classifier:

1. Preprocess the data:
    ```python
    python preprocess.py
    ```

2. Train the model:
    ```python
    python train.py
    ```

3. Evaluate the model:
    ```python
    python evaluate.py
    ```

4. Predict the class of a new SMS message:
    ```python
    python predict.py --message "Your message here"
    ```

## Dataset
The dataset used in this project consists of labeled SMS messages indicating whether each message is spam or not. You can download the dataset from [here](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

## Model
The classifier uses machine learning models such as Naive Bayes, Support Vector Machines, or any other suitable algorithm. The `train.py` script handles the training process.

## Results
After training, the model is evaluated using various metrics like accuracy, precision, recall, and F1-score. The results are displayed in the console and saved in the `results` directory.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Create a new Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for the SMS Spam Collection dataset.
- The contributors who helped in improving this project.


