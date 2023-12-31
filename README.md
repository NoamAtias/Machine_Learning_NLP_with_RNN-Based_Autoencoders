# Homework 4: NLP with RNN-Based Autoencoders

This Homework focuses on the application of deep learning to natural language processing (NLP) using RNN-based autoencoders. We will be working with a subset of Reuters news headlines to build an autoencoder that can encode and decode news headlines.
### This Homework was done together with Chanel Michaeli.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Assignment Structure](#assignment-structure)
  - [Question 1: Exploring the Data](#question-1-exploring-the-data)
  - [Question 2: Building the Autoencoder](#question-2-building-the-autoencoder)
  - [Question 3: Training the Autoencoder with Data Augmentation](#question-3-training-the-autoencoder-with-data-augmentation)
  - [Question 4: Analyzing the Embeddings](#question-4-analyzing-the-embeddings)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

In this assignment, we aim to apply deep learning techniques to natural language processing, specifically using RNN-based autoencoders. Our goal is to build an autoencoder model that can effectively encode and decode news headlines. By learning meaningful representations of the headlines, we can explore various applications such as text generation and headline analysis.

## Dataset

The dataset for this assignment consists of a subset of Reuters news headlines collected over a span of 15 months, covering 2018, 2019, and a few months of the current year. The headlines will serve as the input for our autoencoder model. The dataset provides a rich source of text data for training and evaluating the performance of our model.

## Assignment Structure

This assignment is divided into several questions, each addressing a specific aspect of building and analyzing the autoencoder model. The structure of the assignment is as follows:

### Question 1: Exploring the Data

In this question, we will explore the dataset, analyze the distribution of headlines, and gain insights into the characteristics of the news headlines we will be working with.

### Question 2: Building the Autoencoder

Here, we will construct the autoencoder model using Recurrent Neural Networks (RNNs). The model will consist of an encoder that maps a news headline to a vector embedding and a decoder that reconstructs the news headline from the embedding.

### Question 3: Training the Autoencoder with Data Augmentation

We will introduce the concept of data augmentation to improve the robustness of the autoencoder model. Data augmentation techniques, inspired by Shen et al [1], will be applied to enhance the training process and the quality of the learned representations.

### Question 4: Analyzing the Embeddings

In this final question, we will analyze the embeddings generated by the autoencoder. We will explore techniques such as interpolating between headlines to gain insights into the learned representations and evaluate the effectiveness of the autoencoder model.

## Usage

To use the code and reproduce the results of this assignment, follow these steps:

1. Clone the repository: `git clone https://github.com/NoamAtias/Machine_Learning_NLP_with_RNN-Based_Autoencoders.git`
2. Set up the required dependencies and libraries as specified in the assignment instructions.
3. Run the code for each question in the assignment, following the provided instructions and guidelines.
4. Analyze the results and evaluate the performance of the autoencoder model.
5. Feel free to experiment with different configurations, architectures, and techniques to further enhance the performance and explore additional insights.

## Contributing

Contributions to this assignment are welcome. If you find any issues or have suggestions for improvements, please submit a pull request or open an issue in the repository. Let's collaborate to make this assignment even better!
