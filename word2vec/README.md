From _Efficient Estimation of Word Representations in Vector Space_ [1]

>We propose two novel model architectures for computing continuous vector representations of words from very large data sets. The quality of these representations is measured in a word similarity task, and the results are compared to the previously best performing techniques based on different types of neural networks. We observe large improvements in accuracy at much lower computational cost, i.e. it takes less than a day to learn high quality word vectors from a 1.6 billion words data set. Furthermore, we show that these vectors provide state-of-the-art performance on our test set for measuring syntactic and semantic word similarities.

I am following the paper, more than the toolkit [built by the authors](https://code.google.com/archive/p/word2vec/), and have implemented all four models from the paper: the Feedforward Neural Net Language Model (NNLM), the Recurrent Neural Net Language Model (RNNLM), the Continuous Bag of Words Model (CBOW), and the Continuous Skip-Gram Model (Skip-gram) (TODO or at least I will).

[1]: T. Mikolov, K. Chen, G. Corrado, J. Dean. Efficient Estimation of Word Representations in Vector Space. arXiv:1301.3781v3, 2013. https://arxiv.org/pdf/1301.3781.pdf.

[2]: T. Mikolov, I. Sutskever, K. Chen, G. Corrado, J. Dean. Distributed Representation of Words and Phrases and their Compositionality. arXiv:1310.4546v1, 2013. https://arxiv.org/pdf/1310.4546.pdf.