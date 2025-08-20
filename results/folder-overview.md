## Results

This folder contains the raw relevant results from the models predictions for the target epitope. 

The folder contains 4 sets of results: \
- 3 sets of results differing only by the threshold value t (0.3, 0.5, 0.7) for the final multiclass-classification pipeline. \
  Each of these contain the .csv file with their results, and histograms showing the distribution of binding scores for a given peptide.
- 1 folder with results for the inital classification_regression pipeline. \
  This contains 2 .csv files, both run at t = 0.5, but with a differing number of decoys in the training data to higlight the importance of sufficient 0-count interactions.
