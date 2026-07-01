# SPML Task 2 Submission

## Overview

This repository contains my submission for SPML Task 2, which includes both the Base ML and Applied ML tasks.

---

# Base ML

## Level 1 – Custom ResNet

### Objective

Implement a custom ResNet architecture from scratch for image classification on the CIFAR-10 dataset.

### Features

* Custom Residual Blocks
* Residual Skip Connections
* Batch Normalization
* ReLU Activation
* Adam Optimizer

### Dataset

CIFAR-10

### Results

* Test Accuracy: **84.34%**

---

## Level 2 – Custom LSTM

### Objective

Implement a custom LSTM without using built-in recurrent modules to forecast future temperatures using the Jena Climate Dataset.

### Dataset

Jena Climate Dataset

### Preprocessing

* Hourly downsampling by averaging every six consecutive records
* Feature normalization
* Sequence generation
* Train-test split

### Model

* Manually implemented LSTM Cell
* Hidden Size: 64
* Prediction Horizon: 12 hours

### Evaluation

* Huber Loss: **0.000543**
* MAE: **0.024165**
* MSE: **0.001087**

---

# Applied ML

## Healthcare Evidence-Based Assistant

### Objective

Develop a Retrieval-Augmented Generation (RAG) based healthcare assistant that answers questions using WHO COVID-19 Guidelines.

### Features

* PDF document ingestion
* Text chunking
* Sentence embeddings
* FAISS vector database
* Semantic retrieval
* FLAN-T5 answer generation
* Gradio web interface

### Technologies

* Python
* PyTorch
* Sentence Transformers
* FAISS
* Transformers
* PyMuPDF
* Gradio

---

# Repository Structure

```text
SPML_Task2/
│
├── Base_ML/
│   ├── Level1_Custom_ResNet.ipynb
│   ├── custom_resnet_cifar10.pth
│   ├── Level2_Custom_LSTM.ipynb
│   └── custom_lstm.pth
│
├── Applied_ML/
│   ├── code/
│   ├── architecture/
│   ├── outputs/
│   └── report/
│
└── README.md
```

---

# Author

Karthik Allakki
