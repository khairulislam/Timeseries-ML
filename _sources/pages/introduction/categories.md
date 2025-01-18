# Definitions

A time series is a collection of data points that are recorded at regular intervals over time. Time series data can be used to analyze patterns and trends, and to make predictions about the future.

The categories of time series varies depending on data, task or representation.

## Data Type

Time series data needs to be ordered over time and based on the input data available it can be of the following types:

* *Univariate*: Data where a single variable is tracked over time. For example, past electricity usage to predict future usage.
* *Multivariate*: Where multiple variables are tracked over time for the same instance. For example, past electricity usage as well as hour, day of the week, location to predict future usage.
* *Panel*: Data where the variables (univariate or multivariate) are tracked for multiple instances. For example, multiple quarterly economic indicators for several countries or multiple sensor readings for multiple machines.

## Learning Tasks

Based on which tasks they are performing time series can be of the following categories:

* *Classification*: Predict a categorical target class for a time series.
* *Regression*: Predict a continuous target value.
* *Forecasting*: Predict future values of the input series. The future timesteps are called `Horizon`. When the number of future timesteps to predict is > 1, it is called a `Multi-horizon` problem.
* *Clustering*: Discover groups consisting of instances with similar time series.
* *Annotation*: This focuses on representation learning to perform outlier detection, anomaly detection, change point detection and segmentation.
