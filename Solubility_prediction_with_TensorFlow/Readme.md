
# Summary of the QSAR model (more information in NN_in_TensorFlow.ipynb notebook above)

## Objectives
Estimating the aqueous solubility of a compound directly from its structure.
## Descriptors (features of the machine learning model) used
EState fingerprint generated from SMILES, molecules' weights
## Tools used
RDKit, Scikit-Learn, TensorFlow, Keras
## Model description
"Shallow" deep learning NN with 1 hidden layer.
## References 
1. Dataset from the website: http://www.vcclab.org/lab/alogps/
2. Ideas and methods used are inspired by Cheminformania blog: https://www.cheminformania.com/.
