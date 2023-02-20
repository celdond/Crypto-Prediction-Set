# Crypto-Prediction-Set

A Set of Models to predict to the trajectories of multiple digital currencies.

## Overview

Cryptocurrencies are a new frontier of investment characterized by their future potential in 
a multitude of markets.  As investments, however, they are highly volatile due to their lacking basis 
in functional worth which makes machine learning models an important tool in tracking their future 
value for trading sake.

## Project Description

The files in this project:
- bitcoin.ipynb: Python Notebook containing all the models and their training
- requirements.txt: The python requirements file for local use

The models in this project are Recurrent Neural Networks built with Keras' LSTM network.

All the data used to train the respective models is historical data starting from the beginning of 
their recorded values.

## Use and Install

This project was coded on a local machine using Python 3.10.7 and the packages described in the included requirements.txt. To mimic this environment, simply clone said repository on a local machine and run the following python command in your desired location.

pip install -r requirements.txt

This project used a virtual environment.

As a Jupyter Notebook, web applications such as Google Colab will be a servicable alternative, and the project should work fine as long as the data is loaded in appropriately.

Data used for training was sourced from Yahoo Finance.  Ensure the data is set to as far back as possible to reproduce results.
