# Identifying human values in arguments: an alternative approach based on topics detection
Text Mining and Sentiment Analysis project

Author: Mathias Cardarello Fierro

This repository contains the working files and notebooks of the study "Identifying human values in arguments: an alternative approach based on topics detection". This work aims to develop an explainable multi-label classification model for labeling new argumentation texts with second-level human values categories. It utilizes the correlation between the topics discussed in the texts, detected using BERTopic, and descriptions of human values, using cosine similarity between arguments and human value embeddings. The performance of the model fitted with a Random Forest algorithm is validated using a test dataset from the [SemEval 2023](https://semeval.github.io/SemEval2023/) task organizers, and further discussed focused on the influence of salience tokens present in the textual arguments.
