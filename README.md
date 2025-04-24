# GMA v2.5 and GMA v3.0
GMA v2.5 and GMA v3.0 are two models I've used to predict a given message belongs to whom in a list of users. GMA v2.5 uses bidirectional
LSTM networks whereas GMA v3.0 fine-tunes RoBERTa model.

In the context of GMA v2.5, using more complicated networks have yielded worse results. For GMA v3.0, I tried fine-tuning BERT, RoBERTa,
XLNet and ALBERT models, as well as training a transformer based network from scratch. RoBERTa outperformed the others massively.

GMAv2.5 has 62-64% test accuracy whereas GMAv3.0 has 68-70%.

Unfortunately, I cannot share the dataset I've used in this project.

