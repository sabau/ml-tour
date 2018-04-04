# Machine learning Talk 2018-04-10

We will discover some of the main features and implement them on a Jupyter notebook.
this repo will contain both the slides and the original file as long as some checkpoints to fast-forward some part of the presentation and skip the trainig of our neural networks.

## Supervised

This is the most generic and introductory task, we will use the same example that will be refined on the ConvNet, and see how they will differ.

## Unsupervised

A classical unsupervised task is the categorization or encoding/decoding. The latter is far more discussed at this moment, but almost never used in practice, so we will focus on a more classical categorization problem
We will see kNN and naive Bayes and when to use one or the other.

## Convolutional NN

In this section we will discover why conv nets surpasses classical method for data where correlations between dimensions does matter.
The example will focus on images and in particular on how close pixels influences one another, where on classical NN the concept of neighbour is not exploited.


## Recurrent NN

We will discuss about the needs and the main implementations of this technique.
the example will foxus on time series, in particular text translation: the hardest version of RNNs as it takes a sequence with arbitraty length and output another sequenct of (maybe) different length
