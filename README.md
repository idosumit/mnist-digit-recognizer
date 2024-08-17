# Digit Recognizer

[using the MNIST dataset](https://www.kaggle.com/competitions/digit-recognizer/overview)

## Description

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

The goal is to correctly identify digits from a dataset of tens of thousands of handwritten images. We’ve curated a set of tutorial-style kernels which cover everything from regression to neural networks. We encourage you to experiment with different algorithms to learn first-hand what works well and how techniques compare.

## Practice Skills

- Computer vision fundamentals including simple neural networks
- Classification methods such as SVM and K-nearest neighbors

## Evaluation

### Goal

The goal in this competition is to take an image of a handwritten single digit, and determine what that digit is.

For every in the test set, you should predict the correct label.

### Metric

This competition is evaluated on the categorization accuracy of your predictions (the percentage of images you get correct).

### File Format

The file should contain a header and have the following format:

```
ImageId,Label
1,0
2,0
3,0
etc.
```
