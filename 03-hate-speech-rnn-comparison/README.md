# Hate Speech RNN Comparison

Group coursework project focused on classifying hate speech intensity using recurrent neural network architectures.

## Contents

This project compares several recurrent neural network models for multiclass text classification.

The task consists of predicting the intensity level of hate speech messages using five ordered classes. The notebook includes text preprocessing, vectorization, model training, evaluation and comparison of recurrent architectures.

## Topics

* Text classification
* Hate speech intensity classification
* Text preprocessing
* Stopword removal
* Text vectorization
* Recurrent neural networks
* Vanilla RNN
* LSTM
* Bidirectional LSTM
* GRU
* Bidirectional GRU
* Class imbalance
* Class weights
* Model comparison

## Project File

* `hate_speech_rnn_comparison.ipynb`: notebook comparing recurrent neural network architectures for hate speech intensity classification.

## Dataset

The dataset is not included in this repository because it contains sensitive text content and redistribution rights are not guaranteed.

The notebook expects a local `dataset.csv` file with the following columns:

* `CONTENIDO A ANALIZAR`: text message to classify.
* `INTENSIDAD`: hate intensity label from 1 to 5.

## Academic Context

This project was developed as group coursework for the MSc in Artificial Intelligence.

The published version preserves the original methodology, code and results. Changes are limited mainly to repository organisation, file naming and presentation.
