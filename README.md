![Python](https://img.shields.io/badge/python-3.12%2B-success)
[![License: BSD](https://img.shields.io/badge/license-BSD-success.svg)](https://github.com/trainindata/forecasting-with-machine-learning/blob/main/LICENSE)
[![Powered by Train in Data](https://img.shields.io/badge/Powered%20By-TrainInData-orange.svg)](https://www.trainindata.com/)

# Forecasting with Machine Learning

Learn how to forecast time series with machine learning models: from turning time series into tabular data, to single-step and multistep forecasting, multiseries forecasting, backtesting, and error metrics.

This repository contains the practical notebooks for the **[Forecasting with Machine Learning](https://www.trainindata.com/p/forecasting-with-machine-learning)** course. The examples use pandas 3, scikit-learn, Feature-engine, and skforecast.

**Released:** March 2024
**Last updated**: Nov 2026
**Status:** Actively maintained

[<img src="./FWML-Logo.png" width="248" alt="Forecasting with Machine Learning">](https://www.trainindata.com/p/forecasting-with-machine-learning)

## What you will learn

- Frame time series forecasting as a regression problem.
- Tabularize time series with lag, window, and datetime features.
- Build benchmark models to know whether machine learning is adding value.
- Forecast multiple steps ahead with recursive and direct strategies.
- Forecast many time series at once with global models.
- Evaluate forecasting models with backtesting and choose the right error metric.

## Course contents

1. [**Forecasting as regression**](01-forecasting-as-regression)
   - Time series forecasting
   - Tabularizing time series: lag, window, and datetime features
   - Endogenous and exogenous variables
   - Feature engineering with Feature-engine
   - Benchmark models: naive, seasonal naive, moving average
   - Single-step forecasting with machine learning

2. [**Multistep forecasting**](02-multistep-forecasting)
   - Recursive forecasting
   - Recursive forecasting with window features and future-known features
   - Direct forecasting with skforecast and scikit-learn
   - Direct forecasting with future-known features

3. [**Multiseries forecasting**](03-multiseries-forecasting)
   - Global vs local forecasting
   - Independent multi-time series forecasting
   - Dependent multi-time series forecasting

4. [**Backtesting**](04-backtesting)
   - Backtesting with or without refitting
   - Backtesting with expanding or rolling training windows
   - Backtesting with intermittent refitting
   - Backtesting with a gap

5. [**Error metrics**](05-error-metrics)
   - Choosing error metrics for forecasting
   - Implementing and using custom error metrics

## Getting started

Clone the repository (Python 3.12+ required), then set up a dedicated environment to run the notebooks.

**Create and activate a virtual environment**

```bash
python -m venv fwml
source fwml/bin/activate        # macOS/Linux
fwml\Scripts\activate           # Windows
```

**Install dependencies**

```bash
pip install -r requirements.txt
```

**Install Jupyter and register the kernel**

```bash
pip install jupyter ipykernel
python -m ipykernel install --user --name=fwml --display-name "fwml"
```

The environment will now be available as a kernel named **fwml** in Jupyter Notebook. Start Jupyter and open the notebooks in numerical order:

```bash
jupyter notebook
```

## Course

For lectures, explanations, and the complete learning path, visit the [online course](https://www.trainindata.com/p/forecasting-with-machine-learning).
