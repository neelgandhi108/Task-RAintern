# Task-RAintern
Task-1 to 3

## Task1

In this competition, you're challenged to use the Speech Commands Dataset to build an algorithm that understands simple spoken commands. By improving the recognition accuracy of open-sourced voice interface tools, we can improve product effectiveness and their accessibility. For more details: https://www.kaggle.com/c/tensorflow-speech-recognition-challenge/overview

Evaluation: 
Make a detailed report of  the experiments you have done and your observations. Which approach is better and why? It can be as detailed as you want it to be. Include results in the form of tables and figures. Please do not write them in a paragraph. Please restrict it to a maximum 0f 5 pages including references. Use whatever resources you can find and cite them.

Code-base of all the experiments.  Follow general instructions strictly. 

In the README.md mention the rank, score and entry.


## Task2

Use this dataset (https://www.dropbox.com/s/pan6mutc5xj5kj0/trainPart1.zip) to train a CNN. Use no other data source or pretrained networks, and explain your design choices during preprocessing, model building and training. Also, cite the sources you used to borrow techniques. A test set will be provided later to judge the performance of your classifier. Please save your model checkpoints.


Next, select only 0-9 training images from the above dataset, and use the pretrained network to train on MNIST dataset. Use the standard MNIST train and test splits (http://yann.lecun.com/exdb/mnist/). How does this pretrained network perform in comparison to a randomly initialized network in terms of convergence time, final accuracy and other possible training quality metrics? Do a thorough analysis. Please save your model checkpoints.


Finally, take the following dataset (https://www.dropbox.com/s/otc12z2w7f7xm8z/mnistTask3.zip), train on this dataset and provide test accuracy on the MNIST test set, using the same test split from part 2. Train using scratch random initialization and using the pretrained network part 1. Do the same analysis as 2 and report what happens this time. Try and do qualitative analysis of what's different in this dataset. Please save your model checkpoints.

## Task 3

Assignment Details-
Use a given dataset to build a model to predict the category using description. Write code in python. Using Jupyter notebook is encouraged. 

Show how you would clean and process the data
Show how you would visualize this data
Show how you would measure the accuracy of the model
What ideas do you have to improve the accuracy of the model? What other algorithms would you try?

About Data : You have to clean this data, In the product category tree separate all the categories, figure out the primary category, and then use the model to predict this.
If you want to remove some categories for lack of data, you are also free to do that, mention this with explanation and some visualization.
Questions are made this way to check if candidates are able to understand this.


.
Note: 1) Goal is to predict the product category.
2) Description should be the main feature. Feel free to use other features if it'd improve the model.
3) Include a Readme.pdf file with approach in detail and report the accuracy and what models were used.
 

Dataset link:
https://docs.google.com/spreadsheets/d/1pLv0fNE4WHokpJHUIs-FTVnmI9STgog05e658qEON0I/edit?usp=sharing
