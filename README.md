# Classifier Comparison on the Census data

This project is a descriptive analysis of various supervised learning classifiers like Decision Tree, Random Forest, Naive Bayesian, Support Vector Machines and Neural Network.

### Dataset
* The dataset is taken from the UCI repository from [here](http://archive.ics.uci.edu/ml/datasets/Adult).
* The dataset contains 14 attributes describing an individual personal and working condition.
* The class label is income column giving the information whether an individual's yearly income is less than or greater that equal to 50K.

### Getting Started
  - The code is written in python using various libraries like pandas, numpy and sklearn.
  - I have used Jupyter notebook for easier understanding and execution of the codes.
  - Tutorial on how to use [Jupyter](https://jupyter.readthedocs.io/en/latest/) notebook 

If any libraries are missing on the system simply pip install them and re-run the code
```
pip install <module>
```

### Project Files
I have divided the code into 6 jupyter files where the first 5 files are running the a specific classifier and the [compiler](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/Compiler.ipynb) file simply compares the results and plot the data.

The files corresponding to each classifier is as following:-
*	[Decision Tree](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/Decision_tree.ipynb)
*	[Random Forest](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/RandomForest.ipynb)
*	[Naive Bayes](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/NaiveBayes.ipynb)
*	[SVM](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/SVM.ipynb)
*	[NeuralNet](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/NeuralNetworks.ipynb)


### Results

* #### Confusion matrix
	![alt text](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/ConfusionMatrix.png)
* #### ROC curve
	![alt text](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/ROCplot.png)
* #### Scores
	![alt text](https://github.com/ritvikkhanna09/Census-classifier-comparison/blob/master/Scores.png)
    

## Author

Ritvik Khanna

[contact](mailto:ritvikkhanna09@gmail.com)