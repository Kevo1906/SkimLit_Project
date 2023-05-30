# SkimLit Project

The purpose of this project is to build an NLP model that makes reading medical abstracts easier. The model replicates the deep learning model described in the 2017 paper [*PubMed 200k RCT: a Dataset for Sequenctial Sentence Classification in Medical Abstracts*](https://arxiv.org/abs/1710.06071)

## Problem Statement

The number of RCT papers released is continuing to increase, and those without structured abstracts can be hard to read, which slows down researchers moving through the literature.

## Solution

The solution is to create an NLP model that classifies abstract sentences into their corresponding roles (e.g., objective, methods, results, etc.). This enables researchers to skim through the literature and dive deeper when necessary.

## Model Input

The model takes sentences from medical abstracts as input.

## Model Output

The model returns the abstract sentences classified into their respective roles, including objective, methods, results, and conclusions.

## File Descriptions

- `Project_SkimLit.ipynb`: Jupyter Notebook containing the code for training and evaluating the NLP model.
- `models/`: Directory to save the trained models.
- `README.md`: This file, providing an overview of the project.

## Results

Due to the hardware provided by Google Colab just allow us to train the model for 3 epochs but we obtain an **87.90 %** of accuracy 
