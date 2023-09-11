# Out-of-Sample Price Prediction Tutorial

![Alt Text](./sketch.png)

Welcome to the "Out-of-Sample Price Prediction Tutorial" repository! In this tutorial, we'll explore how to predict prices out of sample using machine learning techniques, with a focus on Facebook Prophet. 

**Disclaimer: This tutorial is for educational purposes only and should not be interpreted as trading advice. The provided code, timestamps, and datasets are used for visualization and experimentation purposes and may not represent a realistic trading model.**

By following the steps below, you'll be able to understand the code and get started with your price prediction project.

## Installation

To begin, you'll need to install the Prophet library. You can find installation instructions for Prophet in the official documentation [here](https://facebook.github.io/prophet/docs/installation.html#python).

Once you have Prophet installed, you're ready to get started!

## Quick Start

Prophet provides a quick start guide that will help you familiarize yourself with its Python API. We recommend reading through the quick start guide and trying out the provided code examples. You can find the guide [here](https://facebook.github.io/prophet/docs/quick_start.html#python-api).

After going through the quick start guide, you'll have a better understanding of how Prophet works and how to use it for time series forecasting.

## Understanding the Code
Once you have done the quick start, have a look at [the code](py_example.py) and [the sketch](sketch.png). In this example, we'll be using Yahoo Finance as our dataset for price prediction. You can easily install the `yfinance` library, which provides a convenient way to access Yahoo Finance data, using pip:

```bash
# Install yfinance for Yahoo Finance data
pip install yfinance 
# Install prophet to forecasting time series data
python -m pip install prophet
# For working with the datasets
pip install pandas
