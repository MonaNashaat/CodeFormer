# CodeFormer
we present CodeFormer, a novel approach to learning unsupervised representations of source code using attention-based networks. The model builds a bidirectional transformer encoder trained with masked tokens to model programming languages. As the figure shows, the model consists of two main stages. In the first stage, we train a bidirectional encoder representation model using a large corpus of code program files. In this stage, a percentage of the input vector is randomly replaced with a special token. Then, the model is trained to predict these masked values. In the second stage, the model is fine-tuned with a set of labeled instances for the task of software defect detection.

<img width="328" alt="image" src="https://github.com/MonaNashaat/CodeFormer/assets/21979050/251f346a-1b5c-4ffe-b123-2ea9fbb71734">

## Installation
To install the model, you can clone the Git repository and run:

    pip install -e .

within it.


