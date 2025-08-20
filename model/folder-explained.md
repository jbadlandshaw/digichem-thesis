## Model

This folder contains all the necessary files needed and used to create, train and test the promiscuity pipeline created as part of the project. 

TB_Local.ipynb is the notebook containing the local installation of TransformerBeta through which the target epitope was run through. \
output_analysis.csv is the output from the TransformerBeta model, of which the top 10 ranked peptides were used to test the models. \
model_training_data.csv is the formatted training data with decoys used to train the models. \
PROMISCUITY_SCORE.ipynb is the notebook file containing instructions on how to train, test and evaluate the models performance.

_Note: 'train_data.npy' is the raw dataset from which the curated dataset for the models was created, and is too large to be uploaded to GitHub. This file can be sourced from https://huggingface.co/hz3519/TransformerBeta_models/tree/main/model_M_retrain_
