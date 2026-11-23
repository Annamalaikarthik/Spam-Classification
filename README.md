# Spam Classification Project

This repository contains a machine learning model designed to classify messages as spam or ham (not spam).

## Overview

The goal of this project is to accurately identify unsolicited and unwanted messages using natural language processing and classification algorithms.

## Dataset

The model is trained on a labeled dataset of text messages. The data is preprocessed to remove noise and extract relevant features for classification.

## Features

- Text preprocessing (tokenization, stop word removal, stemming/lemmatization)
- Feature extraction (TF-IDF, Bag of Words)
- Model training and evaluation
- Prediction on new, unseen messages

## Usage

To run the classification script, use the following command:

```bash
python classify.py --input "Your message here"
```

## Results

The model's performance is evaluated using accuracy, precision, recall, and F1-score. Detailed results can be found in the results directory.
