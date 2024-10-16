# ID3 Algorithm Implementation

This project is an implementation of the ID3 algorithm (a machine-learning algorithm for decision trees) in Python. It was developed as part of my Bachelor's degree in Artificial Intelligence at the Athens University of Economics and Business. Specifically, it was created for the AI course, where I applied the algorithm to classify textual data into two distinct categories (e.g., positive/negative sentiment).

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

## Introduction

The ID3 algorithm implemented in this project can be used for text classification tasks. The project uses the well-known "IMDB Movie Review Dataset" to showcase the capabilities of the classifier. Learning curves and tables showing accuracy, precision, recall, and F1-score for the training and test datasets are generated based on different numbers of training examples.

## Features
- ID3 algorithm implementation for text classification
- Supports learning curve generation
- Produces metrics including accuracy, precision, recall, and F1-score
- **Adjustable hyperparameters for word frequency filtering in the dataset**:
   - You can control which words are considered in the classification process by setting minimum and maximum frequency thresholds.

## Installation

To install and run this project, clone the repository and ensure you have the necessary dependencies installed:

```bash
git clone https://github.com/theGreatDane-coder/id3Algorithm.git
cd id3Algorithm
jupyter notebook ID3_demo.ipynb
