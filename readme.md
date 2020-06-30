### Readme

**This repository contains implementation of GONET in jupyter notebook**

You should download datasets mentioned in our paper, and use the scripts to train the model.

Model details:

sequence data: mapping to matrix using ProVec ,i.e. each trigram is represented by a 100d dense vector, so each protein sequnce is mapped to a 1500*100 matrix.
    feature extraction of sequence data: recurrent CNNS followed by attention.

PPI data: 
   utilize network representation learning to get embeddings of each protein node, concat this vector with sequence feature to predict labels.

**Important:**
i write the codes in different machines, so the datapathes in the scripts may be incorrect,please update the path with respect to the true path.
what is more, hyper-parameters in our model is not the best, which means you can change them to get better results.
