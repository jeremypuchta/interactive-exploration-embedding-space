# Embedding Space Explorer

The _Embedding Space Explorer_ is a prototypical systems that allows its users to interatively explore a multi-dimensional embedding space.
It was built as part of the master thesis with the title _Interactive Exploration of Embedding Spaces_.

The thesis focused specifically on the fashion domain, but it is feasible to apply the shown approach to other domains.

## Contents

* _fashion-embeddings-global-view.ipynb_: Contains the global visualization of the embedding space. This allows users to obtain insights about the high-dimensional structure of the vector spaces their are working with. 

* _interactive-exploration-[2/3]D-embedding-space.ipynb_: Prototypical implementations for low-dimensional vector spaces that are illustrating and validating the presented approach.

* _interactive-exploration-nd-embedding-space.ipynb_: Prototypical implementation for multi-dimensional vector spaces. Containing the code for evaluation the computed latent dimensions, too.

* `resnet-50-embeddings.pkl`: Pickle file containing the embedding vectors computed from the [Fashion Product Images Dataset](https://www.kaggle.com/paramaggarwal/fashion-product-images-dataset).

## Getting Started

The system was built using Python 3.8.7. It is recommended to use a virtual environment (`venv`) to install all necessary libraries. These can be found in the `requirements.txt` file.
