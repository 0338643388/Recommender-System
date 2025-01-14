# Recommender-System

## Overview
This project aims to develop a product recommendation system for consumers based on implicit feedback using collaborative filtering.

## Table of Contents
- Features
- Technologies Used
- Installation
- Usage
- Data Sources
- Model Training
- License

## Features
- Data Processing: Cleans and prepares the data for analysis.
- Model Selection: Implements Multiple Deep Learning algorithms: NeuMF, MLP, GMF
- Visualization: Provides visual insight about consumer behaviour and model performance.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Pytorch
- Jupyter Notebook

## Installation
To set up the project locally, follow these steps:
 1. Clone the repository:
```bash
git clone https://github.com/0338643388/Recommender-System.git
```
 2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage
1. Open the Jupyter Notebook file located in the notebooks directory.
2. Run the cells sequentially to execute data preprocessing, model training.
3. Modify parameters as needed to experiment with different models or datasets.

## Data Sources
- UCI Responsitory Machine Learning

## Model Training
The project includes scripts for training different models. The primary steps are:
  1. Load and process the data
  2. EDA is used to discover trends, behaviours about consumers
  3. Preprocess before training models.
  4. Split the dataset into training and testing sets.
  5. Train the selected model using the training set.
  6. Evaluate model performance using Hit Rate and NDCG.
