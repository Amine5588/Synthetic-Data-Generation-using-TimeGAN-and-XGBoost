# Synthetic Data Generation using TimeGAN and XGBoost

This project demonstrates the generation of synthetic data for simulating sports events, specifically football games. We utilize the TimeGAN model for sequence generation and an XGBoost classifier for action labeling.

## Table of Contents
- [Introduction](#introduction)
- [Data Preparation](#data-preparation)
- [Model Training](#model-training)
- [Synthetic Data Generation](#synthetic-data-generation)

## Introduction

In sports analytics, having access to real-world data is often limited. Therefore, generating synthetic data that closely resembles real data is valuable for various applications, such as machine learning model development and simulations. This project focuses on the generation of synthetic football game data, including player movements and actions.

## Data Preparation

We begin by collecting and preparing real soccer game data. This data includes information about player movements, such as position and speed, as well as specific actions like passes, tackles, and shots. The data is structured into a tabular format to facilitate analysis.

## Model Training

To generate synthetic data, we employ the TimeGAN model. TimeGAN is a generative adversarial network designed for sequential data. We train TimeGAN using our preprocessed real-world football game data. The training process involves setting hyperparameters and specifying the model's architecture.

## Synthetic Data Generation

Once the TimeGAN model is trained, we can use it to simulate new football game data. The generated data consists of player movements and actions. The generated actions are initially encoded as categories, which are later converted into human-readable labels.



**Note:** In this project, we used Python with libraries such as Pandas, Scikit-learn, XGBoost, and TimeGAN. You can find code snippets and additional details in the provided Jupyter Notebook.

For detailed instructions, check the project's Jupyter Notebook.

## Contributor
- [KAROUI Amine]



