# EACVP
The ESM-2 LM combined with the framework of CNN and CBAM attention to predict anti-coronavirus peptides.  
ESM.ipynb is used to characterize peptide sequences and CBAM.ipynb is used to predict, but ESM is not suitable for sequences that are too long and will cause program termination.
The anticov_train.csv and anticov_test.csv are labeled training set and test set. The file contains positive and negative samples. Input anticov_train.csv into ESM.ipynb to get the peptide sequence representation, and input the peptide sequence representation into CBAM.ipynb for prediction and use anticov_test.csv for testing.
