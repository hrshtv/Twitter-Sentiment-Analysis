# Sentiment Analysis on Twitter Data

Dataset used: [Sentiment140](https://www.kaggle.com/kazanova/sentiment140)  

**Models:** 
- [Keras-BiLSTM-with-MHSA.ipynb](Keras-BiLSTM-with-MHSA.ipynb): A Bidirectional LSTM classifer implemented in Keras with a custom layer for computing the multi-headed self attention
- [PyTorch-BiLSTM-with-MHSA.ipynb](PyTorch-BiLSTM-with-MHSA.ipynb): Similar network, but implemented in PyTorch

**Older models:**  
- [old/Keras-Simple-BiLSTM.ipynb](old/Keras-Simple-BiLSTM.ipynb): A vanilla Bidirectional LSTM classifer
- [old/PyTorch-Simple-BiLSTM.ipynb](old/PyTorch-Simple-BiLSTM.ipynb): Same, but in PyTorch
- [old/Keras-Improved-BiLSTM.ipynb](old/Keras-Improved-BiLSTM.ipynb): Better preprocessing, lower complexity of the model
- [old/Keras-BiLSTM-with-MHSA-v1.ipynb](old/Keras-BiLSTM-with-MHSA-v1.ipynb): This has a minor bug, when the tensors are passed from the MHSA layer to the Dense laye we don't flatten it, Keras doesn't given an error even if we pass the 2D tensor to a Dense layer. This has been included because it still gives considerably good results.

  
