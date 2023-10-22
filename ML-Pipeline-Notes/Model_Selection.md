# Model Selection for SRE Predictive Analysis

## Project Goal

The goal is to develop a machine learning model that is technically capable of automating the predictive analysis tasks commonly handled by an SRE. 

## Table of Contents

1. [Objective](#objective)
2. [Implementation Steps](#implementation-steps)
3. [Types of Models](#types-of-models)
    - [Supervised Models](#supervised-models)
    - [Unsupervised Models](#unsupervised-models)
    - [Time Series Models](#time-series-models)
    - [Hidden Markov Models](#hidden-markov-models)
4. [Evaluation Metrics](#evaluation-metrics)
5. [SRE Relevant Metrics](#sre-relevant-metrics)
6. [Tools and Technologies](#tools-and-technologies)

---

## Objective

To choose machine learning models that can automate the technical analysis usually performed by an SRE.

## Implementation Steps

- Evaluate different types of models like supervised, unsupervised, and time-series models

## Types of Models

### Supervised Models

#### Examples

- Decision Trees
- Random Forest
- Support Vector Machines (SVM)

#### Special Features

- Can handle both numerical and categorical data
- Decision Trees are easy to interpret

#### How It Helps With SRE Metrics

- Capable of predicting incidents based on metrics like latency and error rates, which are essential for maintaining SLOs.

### Unsupervised Models

#### Examples

- K-means clustering
- DBSCAN

#### Special Features

- K-means is good for spherical clusters
- DBSCAN can find arbitrarily shaped clusters

#### How It Helps With SRE Metrics

- Useful for anomaly detection in system metrics like error rate and saturation, enabling preemptive action.

### Time Series Models

#### Examples

- ARIMA
- Long Short-Term Memory (LSTM)

#### Special Features

- ARIMA captures linear relationships
- LSTM can capture long-term dependencies in data

#### How It Helps With SRE Metrics

- Effective for predicting time-based metrics like traffic spikes, allowing for better resource allocation.

### Hidden Markov Models

#### Special Features

- Excellent for systems that can be modeled as Markov processes
- Captures transitions between states

#### How It Helps With SRE Metrics

- Capable of predicting sequence-based changes in system states, useful for metrics like uptime and saturation.

## Evaluation Metrics

Different models will require different evaluation metrics for optimal performance. Choose the metric that best suits the model and the problem you are trying to solve.

## SRE Relevant Metrics

- **Latency**: The time it takes to service a request.
- **Traffic**: The number of requests hitting the service.
- **Error Rate**: The rate of failed requests over total requests.
- **Saturation**: How "full" the service is.
- **Uptime**: The amount of time a service is available.

## Tools and Technologies

- scikit-learn
- TensorFlow