# Paper: Key Point Analysis via Contrastive Learning and Extractive Argument Summarization

This is the code for the paper *Key Point Analysis via Contrastive Learning and Extractive Argument Summarization*.

Milad Alshomary, Timon Gurcke, Shahbaz Syed, Philipp Heinrich, Maximilian Spliethöver, Philipp Cimiano, Martin Potthast, Henning Wachsmuth


# Code

## Track1:

For argument and key-point matching the following experiment notebooks should be executed:

- The `1.experiment-data-prep.ipynb` notebook contains the code that prepare the data for training the siamese model (sbert)
- The `2.experiment-sbert-training.ipynb` notebook contains the code to train the key-point matching model
- The `3.experiment-evaluation.ipynb` notebook contains the code to generate predictions and evaluate the model



## Track2:

For key-point generation the following experiment notebooks should be executed:

- The `4.experiment-data-prep-for-track-2.ipynb` notebook contains the code that generate argumentative quality scores needed to run the ArgPageRank
- The `5.experiment-page-rank.ipynb` notebook contains the code to generate the key-points using the ArgPageRank
- The `6.experiment_evaluation.ipynb` notebook contains the code to perform the final evaluation

