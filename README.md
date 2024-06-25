# Stock Trading Signal Prediction with Transformer Models

This repository contains the implementation of a transformer-based machine learning model designed to predict trading signals (buy, sell, hold) based on high-frequency trading data. The project integrates traditional trading strategies with modern machine learning techniques to enhance trading decision-making processes.

## Project Overview

The aim of this project is to develop a predictive model that can generate actionable trading signals from microsecond-level stock price data. It combines technical indicators and a transformer architecture to analyze patterns and suggest trading actions.

## Dataset

The dataset consists of high-frequency trading data, which includes features like price, volume, and various technical indicators (e.g., RSI, MACD). 

## Model

The core of this project is a transformer model tailored to process time-series financial data. The model is trained to recognize patterns that precede buy, sell, or hold signals.

### Technical Details:
- **Input Features**: Price, Volume, RSI, MACD, Stochastic Oscillator K
- **Output**: Trading signals (0 = Buy, 1 = Sell, 2 = Hold)


## Files in the Repository

- `Transformer_signal.ipynb`: Jupyter notebook containing the model training and evaluation code.
- `weights_batch128/`: Folder containing the trained model weights.
- `pics_batch128/`: Loss plots generated during training.


## How to Use

1. Clone the repository.
2. Install required dependencies: `pip install -r requirements.txt`
3. Run the Jupyter notebook to train the model or load pre-trained weights to simulate trading.

