This folder contains all the genes-related files

The benchmark file contains the indices of disease genes and 50 sets of non-disease genes corresponding to the order in "GeneList_v1.2.txt". The file is a dictionary and can be loaded by the following code

[import pickle]

[with open('benchmark_1.1_3', 'rb') as fp:]
    [Bench = pickle.load(fp)]
    
Bench[0] contains the indices of disease genes, Bench[1] to Bench[50] contains the indices of the 50 sets of non-disease genes. Bench[51] contains the union of the 50 sets of non-disease genes.
