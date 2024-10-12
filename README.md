# Cricket Runs Prediction using Duckworth-Lewis-Stern Method

## Introduction

This repository contains a Jupyter notebook that implements the Duckworth-Lewis-Stern (DLS) method for predicting runs in cricket matches. The DLS method is a mathematical formulation used to calculate target scores in limited-overs cricket matches interrupted by weather or other circumstances.

In this project, we tackle the problem of predicting the expected number of runs a cricket team will score given the number of overs remaining and wickets in hand. This prediction is crucial for setting fair targets in interrupted matches and understanding the dynamics of run-scoring in cricket.

## Contents

The main component of this repository is the Jupyter notebook `jupyter notebook copy.ipynb`, which includes:

1. Theoretical background on the DLS method
2. Data preprocessing of ODI cricket matches from 1999 to 2011
3. Implementation of the DLS model
4. Model fitting process
5. Visualization of results
6. Analysis of the common slope parameter

## Key Features

- Implements the DLS method formula: Z(u, w) = Z_0(w)[1 - exp{-L(w)u/Z_0(w)}]
- Estimates Z_0(w) and L(w) parameters for different wicket scenarios
- Provides visualizations of the model's predictions
- Calculates a weighted average L value for all wicket scenarios

## Requirements

- Python 3.x
- Jupyter Notebook
- Libraries: numpy, scipy, pandas, matplotlib

## Usage

1. Clone this repository
2. Ensure you have the required Python libraries installed
3. Open and run the `jupyter notebook copy.ipynb` file in Jupyter Notebook

## Results

The notebook produces various outputs including:

- Preprocessed dataset statistics
- Trained model parameters
- Visualizations of the DLS model predictions
- Analysis of wicket weights and the common slope parameter

This project provides insights into cricket run-scoring patterns and can be useful for cricket analysts, enthusiasts, and anyone interested in sports analytics.
