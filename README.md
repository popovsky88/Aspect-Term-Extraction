# Aspect-Term-Extraction

This project seeks to explore the topic of Aspect-Based Sentiment Analysis (ABSA) and focuses on the fundamental step of ABSA, which is the Aspect Term Extraction (ATE) task. Taking the supervised learning pathway, we experimented with both the binary target classifictaion approaches (Multinomial Naïve Bayes, SVM, LR) and the BIO sequence labeling approaches (RNN, LSTM, Bi-LSTM) to address the task. 

We tested the models against the Restaurant and Laptop datasets and conclude that Bi-LSTM, among all RNN-based models, achieves the best performance. Conditional random fields (CRF) layer and pre-trained word embeddings can further enhance the performance of a Bi-LSTM model. 

![alt text](https://github.com/popovsky88/Aspect-Term-Extraction/blob/main/img/Architecture.png)

![alt text](https://github.com/popovsky88/Aspect-Term-Extraction/blob/main/img/Architecture_crf.png)
