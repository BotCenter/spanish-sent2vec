# Spanish Sentence Embeddings

Spanish Sentence Embeddings trained using [sent2vec](https://github.com/epfml/sent2vec) on the [Spanish Unannotated Corpora](https://github.com/josecannete/unannotated-spanish-corpora).

## Pre-Processing

The data used was already preprocessed in [Spanish Unannotated Corpora](https://github.com/josecannete/unannotated-spanish-corpora) to lowercase, remove multiple spaces, remove urls and others. We also used the script to split on punctuation included in the previous repository.

According to that tokenization, the 2.6B words corpus got into 3.4B tokens.

## sent2vec Parameters

We set default parameters of sent2vec to train a unigram + bigram model.

## Download

[Spanish sent2vec](https://storage.googleapis.com/botcenter-public/sent2vec_model.bin) (700 dim sentence embeddings, unigram+bigram model, 14.4 GB)

## References

  Matteo Pagliardini, Prakhar Gupta, Martin Jaggi, [*Unsupervised Learning of Sentence Embeddings using Compositional n-Gram Features*](https://aclweb.org/anthology/N18-1049) NAACL 2018
