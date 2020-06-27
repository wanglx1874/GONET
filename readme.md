### Readme

*This repository contains codes of GONET in jupyter notebook*

You should download datasets mentioned in our paper, and use the scripts to train the model.
Model details:
sequence data: mapping to matrix using ProVec ,i.e. each trigram is represented by a 100d dense vector, so each protein sequnce is mapped to a 1500*100 matrix.
              feature extraction of sequence data: recurrent CNNS followed by attention.

PPI data: utilize node2vec to get embeddings of each protein, concat this vector with sequence feature to predict labels.

