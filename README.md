# Aspect-Term-Extraction

This project seeks to explore the topic of Aspect-Based Sentiment Analysis (ABSA) and focuses on the fundamental step of ABSA, which is the Aspect Term Extraction (ATE) task. Taking the supervised learning pathway, the paper ex-
perimented with both the feature extraction ap-
proaches and the sequence labeling approaches
to address the task. The paper provides a com-
prehensive comparison and evaluation of model
performances between different preprocessing
and modeling framework designs. We tested
the models against the Restaurant and Laptop
datasets and conclude that Bi-LSTM, among all
RNN-based models, achieves the best perfor-
mance. Conditional random fields (CRF) layer
and character embedding can further enhance
the performance of a Bi-LSTM model. Further-
more, the paper evaluates model performances
not only from a macroscopic level using param-
eters like accuracy and F1 score but also from
a microscopic level using specific error cases
selected from the dataset to understand and ex-
plain the impact of the model architecture on
the dataset
