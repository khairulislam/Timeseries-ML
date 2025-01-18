# Libraries

This book will use the following popular libraries:

* [SKTIME](https://www.sktime.net/en/stable/get_started.html): A unified framework for machine learning with time series that supports a wide range of time series tasks {cite}`loning2019sktime`.
* [Time-Series-Library (TSLib)](https://github.com/thuml/Time-Series-Library): An open-source library for deep learning researchers, especially for deep time series analysis. It provide a neat code base to evaluate advanced deep time series models or develop your model, which covers five mainstream tasks: long- and short-term forecasting, imputation, anomaly detection, and classification.
* [GluonTS](https://ts.gluon.ai/stable/): A framework for probabilistic time series modeling, focusing on deep learning based models, based on PyTorch and MXNet.
* [Darts](https://unit8co.github.io/darts/): A Python library for user-friendly forecasting and anomaly detection on time series. It contains a variety of models, from classics such as ARIMA to deep neural networks.
* [tsai](https://timeseriesai.github.io/tsai/): An open-source deep learning package built on top of Pytorch & fastai focused on state-of-the-art techniques for time series tasks like classification, regression, forecasting, imputation.
* [PyTorch Forecasting](https://pytorch-forecasting.readthedocs.io/en/stable/): A PyTorch-based package for forecasting with state-of-the-art deep learning architectures. It provides a high-level API and uses PyTorch Lightning to scale training on GPU or CPU, with automatic logging. Though this library has limited models and often has version conflicts.

The package space for time series is highly fragmented, lots of great implementations and methods out there but many different interfaces. Most have very limited customizability.

```{image} ../../images/ts-fragmentation.png
:alt: classification
:width: 90%
:align: center
```
