# GenerativeAI_Pre_Training

Bigram Model Training:
* In this model training, bigrams of all input names are generated using python zip function, then input and output tensors are created. Then every element of input tensor is encoded using one hot encoding(27 1D Vector and the corresponding index of element is 1).
* Random weight matrix is generated using manual seed generator.
* Encoded input tensor is multiplied with Weight tensor to get logits.
* Logits are used to get probabilities of every output.
* Quality of model is obtained using Negative Log Likelihood.
* Using gradient descent approach, grad matrix is obtained, which is used to adjust weights using learning rate.
