# CS6375 Course Project
## ArXiv Paper Tagger

This project aims to use supervised learning methods to build a model that can predict tags for a given arXiv paper.


# Files

Dataset can be downloaded from https://www.kaggle.com/datasets/Cornell-University/arxiv

## Libraries and dependencies

Python 3.9.12
scikit-learn 1.0.2
nltk 3.7
fasttext 0.9.2
## System Information:
macOS 13
16 GB RAM
Minimum 5GB of disk space.

## How to execute?
- Download the data from the kaggle link and execute the Arxiv_data_cleaning.ipynb
- To clean up the data, execute the Arxiv_data_159_103.ipynb
- Run the preprocessing_features_fasttext.ipynb and preprocessing_features_tfidf.ipynb notebooks for fasttext and tf-idf embeddings.
- To execute a model, navigate to the respective model_embedding notebook.
- If the trained model is already present, uncomment lines in the respective notebook to load the same and skip the training.