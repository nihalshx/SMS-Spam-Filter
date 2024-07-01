# SMS-Spam-Filter [Spam SMS Detection 📨]

SMS-Spam-Filter 📨 utilizes TensorFlow and Keras to detect spam SMS messages. Trained on the SMS Spam Collection Dataset 📩, it preprocesses data, visualizes insights, builds a model, and evaluates accuracy for improved spam detection ✉️.

## Table of Contents
- [Installation](#installation)
- [Dataset](#dataset)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/spam-sms-detection.git
    cd spam-sms-detection
    ```

2. Install the required libraries:
    ```bash
    pip install pandas matplotlib seaborn wordcloud tensorflow keras scikit-learn
    ```

## Dataset

The dataset used is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection), consisting of SMS labeled as ham (legitimate) or spam.

## Preprocessing

1. Load and explore the dataset:
    ```python
    import pandas as pd

    data = pd.read_csv("/content/SMSSpamCollection", sep='\t', names=["label", "message"])
    ```

2. Visualize the data using word clouds
   

## Model Architecture

The model uses an Embedding layer followed by a GlobalAveragePooling1D layer and Dense layers
