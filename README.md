# atpPredictor
This repository contains all the code used for building and using a ATP tennis match result predicting model.
The accuracy of the model depends on how long you have to train it, but with my maximum of 12 hours runtime I have already gotten the model to show positive results, that would be profitable if used to bet over a certain confidence threshold. 

Data is aggregated, cleaned, and new inputs are calculated in Tennis_Model_Data.ipynb, the models are trained in Model_Building.ipynb, and results can be calculated in Model_Usage.ipynb.

The notebooks are set up to connect to drive to save data and trained models for usage.

All the data used to train the model was either calculated from or included in the data in Jeff Sackmann's repository linked here, https://github.com/JeffSackmann/tennis_atp. 
A clone of the repository used for the training is in my repositories.
