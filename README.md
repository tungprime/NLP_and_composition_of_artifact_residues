Determining the composition of artifact residues is a central problem in ancient residue metabolomics. Traditionally, this is done by comparing mass spectra features in common with an experimental pipe and a sample pipe (classical method). While this method is simple and straightforward, its prediction capabilities can be inaccurate. Here, we introduce a novel algorithm (new method) based on ideas from the field of natural language processing to solve this problem.


This GitHub repository contains the data and the codes that we implemented in our article. There are two main methods that we implement. 

# 1. The TF-IDF method 

Here we use three variations of this method. All of them are implemented using the standard Sklearn library. For the first method, we use the classical TF-IDF method. For the second method, we set idf=1. Lastly, for the third method, we use log(tf) instead of tf where tf is the term-frequency. 

# 2. The PMI method

This method is suggested by one of the referees. To the best of our understanding, its implementation is not available in Sklearn so we implement it from scratch (we refer the readers to the main text for a precise description of this method). 

# Results

We refer the readers to the main text for discussions regarding the results of our approach. 
