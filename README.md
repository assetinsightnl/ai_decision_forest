# Classifying the Iris-dataset
Random decision forest example on the Iris dataset. A random decision forest is created and the programmer can change the parameters in order to get to a better understanding of what they do.

If you have installed Python 3 and Jupyter Notebook (possibly through Anaconda) correctly, continue with this readme. Otherwise, if one or more of these elements are not yet installed correctly, first install them.

Walk through the next steps in order to train and test neural random decision forest v0.00001:
1. Jupyter Notebook (through Anaconda)
2. Navigate to the directory in which you have forked or downloaded the code from this repository
3. Scroll through the code. It is not neccesary to understand the all the code.
4. Use the 'run' button on top of the screen to run the code, or select the cell which is to be executed and press 'shift + enter'
5. Continue doing this until all cells were executed
6. In order to change the parameters of the model, change them in the correct cell and re-execute that cell and all cells after that one

Note that in the fourth cell a single decision tree is used as a model and in cell six an entire random forest is used as a model.


### Research questions for 'workshop1a' and 'workshop1a_advanced'
If you are fairly new to python and/or to the sklearn package, start with the 'workshop1a' notebook. If you are familiar with python and/or the sklearn package, start with the 'workshop1a_advanced' notebook.

By editing the parameters in the third cell, the trained model can improve or worsen. Try to answer the following questions:
- What is the effect of shuffling or not shuffling of the data?
- What is an appropriate size for the test set?
- What is the effect of max_depth?
- What is the effect of n_forest_estimators?
- What two columns combined provide the best basis to make predictions with?
- What is your best configuration and why?


### Resarch question for 'workshop1b' and 'workshop1b_advanced'
The code is very similar to the 'workshop1a' and 'workshop1a_advanced' notebooks, except that additional quality tools have been added. Considering these new tools, what is the best configuration you can find and why?
