# SPAM-FILTER
# Spam Detection Using Multinomial Naive Bayes

This project implements a spam detection system using the Multinomial Naive Bayes algorithm. The model is trained on a dataset of SMS messages labeled as "spam" or "ham" (not spam) and can classify new messages based on their content.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Spam detection is a crucial task in email and messaging systems to filter out unwanted messages. This project utilizes the Multinomial Naive Bayes algorithm, which is particularly effective for text classification tasks. The model is built using Python and the Scikit-learn library.

## Dataset

The dataset used in this project is the [SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). It contains 5,572 SMS messages labeled as "spam" or "ham." The dataset is stored in a CSV file named `spam.csv`.

### Dataset Structure

- **Category**: Indicates whether the message is "spam" or "ham."
- **Message**: The text content of the SMS message.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn
