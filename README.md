# pypads-notebooks

This project has sample notebooks on how to run pypads and the whole padre system. This will be mirrored to GitHub so that users can have a first hand look on how to use the Pads infrastructure to run their own experiments

## How the notebooks are organized
The main folders here are single_run and multiple_runs. 


### Custom Dataset
Notebook shows how to use your own Numpy dataset for PyPads tracking

### Decision Tree
A simple Decision Tree experiment using the scikit-learn classifier

### Keras Neural Networks
Shows how to train a classifier on the MNIST dataset which is tracked by PyPads
This notebook also uses both keras based metrics and tracked scikit-learn metrics

### MLP Classifier
An MLP classifier using the scikit-learn MLP algorithm

### PyTorch_NeuralNetworks
A PyTorch example with the Iris dataset. This experiment shows tracking by the PyPads infrastructure.
It also contains information to create your own Neural Network model, custom Data Loader and one hot encoding.
The notebook also tests the model regularly.
The notebook uses the scikit-learn classification report and the accuracy metrics.
