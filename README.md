# Python-AI-Project-2
Code for Project 2 

This is Udacity's second project 'Create Your Own Image Classifier' within their AI Programming with Python Nanodegree Program. 

-- learn.py downloads the users choice of pretrained pytorch architecture and then edits the classifier and initiates 
optimisation. The user can edit the hyperparameters of the model: learning rate, epochs, hidden layers, etc. The learning process 
updates the user on its progress and after it completes a .pth dictionary is returned that will be used in predict.py.

predict.py will load a model checkpoint and then process a single image showing the top n liklihoods of its prediction. 

