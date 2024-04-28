# Identifying human values in arguments: an alternative approach based on topics detection
Text Mining and Sentiment Analysis project

Author: Mathias Cardarello Fierro

This repository presents the files of the work "Identifying human values in arguments: an alternative approach based on topics detection"  This work aims to develop an explainable multi-label classification model for
labeling new argumentation texts with second-level human values categories. It
utilizes the correlation between the topics discussed in the texts and descriptions
of human values. The process involves identifying topics using BERTopic, and
a Random Forest algorithm, along with BERT embeddings of arguments and
topics, is employed to maximize coherence and silhouette scores, indicating mean-
ingful and distinct topics. The performance of the model is validated using a test
dataset from the [SemEval 2023](https://semeval.github.io/SemEval2023/) task organizers, and further discussed focused on
the influence of salience tokens present in the textual arguments.
