
# Project Title

Academic project realized during Biomedical Imaging Master degree at Sorbonne University. 
The aim of this project is to predict digitally reconstructed neurons' class, based on morphological descriptors. 

This project was supervised by Suvadip MUKHERJEE (https://gitlab.pasteur.fr/smukherj)

## Authors

- [@sebgra](https://www.github.com/sebgra)

  
## Installation and requirements

This notebook requires some specific packages : 

* pylmeasure

```bash 
pip install pylmeasure
```
    
## Results

Based on 43 morphological features, on which first order statistics are computed, a classification score (f1-score) of 1.0 is reached by some classifiers. 

![Results Graph](https://github.com/sebgra/NeuroMorpho/blob/main/results/images/Classification_results.png)

## Imporvements

Neuron reconstructions are selected on http://neuromorpho.org/ .
Some neurons can't be read by pylmeasure. Also the dataset is imbalanced. 

It could be interesting to enhance the database by increasing the number of neurons of each class and enhance the number of classes. 

  