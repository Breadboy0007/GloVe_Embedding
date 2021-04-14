# GloVe_Embedding
Using GloVe's pre-trained word vectors to initialize embedding layer

This model uses pre-trained word vectors from GloVe to initialize an embedding layer.  The model is first trained for a few epochs while the embedding layer is frozen.  Then after unfreezing the embedding layer the model is further trained using a lower learning rate.
