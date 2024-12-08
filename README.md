# Fake News Prediction using Machine Learning

This project aims to build a machine learning model to predict whether a given news article is fake or real. The model is trained on a dataset of news articles and uses various natural language processing (NLP) techniques to classify the articles.

## Table of Contents

-   [Introduction](#introduction)
-   [Dataset](#dataset)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Model](#model)
-   [Results](#results)
-   [Contributing](#contributing)
-   [License](#license)

## Introduction

Fake news has become a significant issue in today's digital age. This project leverages machine learning to help identify and classify fake news articles, providing a tool to combat misinformation.

## Dataset

The dataset used for this project consists of labeled news articles. Each article is labeled as either fake or real. The dataset can be found [here](link-to-dataset).

## Installation

To run this project, you need to have Python installed. Follow the steps below to set up the environment:

1. Clone the repository:
    ```bash
    git clone https://github.com/dipto-kainin/Fake-News-Prediction-using-Machine-Learning.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Fake-News-Prediction-using-Machine-Learning
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To train the model and make predictions, run the following command:

```bash
python main.py
```

## Model

The model uses various NLP techniques such as TF-IDF vectorization and machine learning algorithms like Logistic Regression, Naive Bayes, and Support Vector Machines (SVM) to classify the news articles.

## Results

The performance of the model is evaluated using metrics such as accuracy, precision, recall, and F1-score. The results are documented in the `results` directory.
