This work will involve model registries and versioning in MLFlow.  It will use the dataset reg2, 
which a target y and 2 potential predictor variables x1 and x2.  Use scikit-learn for the linear 
regression (for MLFlow, this is the model flavor) (so you will have to split up the data). 


1. Read through the quickstart and model registry tutorials linked in this directory.   
2. Build 3 models: 
a. Try a linear regression model using x1 only to predict y.  Look at how well it 
does.  Call this model model_1. 
b. Try a linear regression model using x2 only to predict y.  Look at how well it 
does.  Call this model model_2. 
c. Finally, use x1 and x2 to predict y.  Compare the errors and R^2 values to the 
previous model.  How do they compare? 
3. To do the version control with MLFlow, follow these steps 
a. Create a repository in your Git for the models 
b. Put the models there. 
c. Register the models in MLFlow (you can use the above names or 
4. Start and view the tracking server for the models. 


Turn in a pdf of your notebook, along with a screen shot of the tracking server and the 
requirements.txt file.
