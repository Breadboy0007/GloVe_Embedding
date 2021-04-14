# GloVe_Embedding
Using GloVe's pre-trained word vectors to initialize embedding layer

This model uses pre-trained word vectors from GloVe to initialize an embedding layer.  The model is first trained for a few epochs while the embedding layer is frozen.  Then the embedding layer is unfrozen and the model is further trained using a lower learning rate.
