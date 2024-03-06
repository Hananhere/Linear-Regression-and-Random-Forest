
# **Linear Regression and Random Forest**

This is a very basic project on simple linear regression and random forest to predict **logS**(log of solubility) given **MolLogP**(measure of compound’s lipophicity), **Molwt**(Molecular Weight), **NumRotatableBonds** (Number of Rotatable Bonds in the molecule) and **Aromatic Proportion**.

The dataset has been divided in 80:20 ratio for the training and testing samples respectively. 


## **MODEL PERFORMANCE**

To evaluate the models, we have used **Mean Square Error(MSE)** and **R^2** as the metrics:

**MSE** : Measures the average squared difference between the predicted and actual values. A lower MSE indicates that the model's predictions are closer to the actual values on average.

**R^2**: It represents the proportion of variance in the dependent variable that can be explained by the independent variables. A higher R² value indicates that the model can explain a greater proportion of the variability in the dependent variable.

Based on the metrics, Linear Regression performs better for this dataset than Random Forest. This can be better seen by observing the scattering in the predicted vs experimental plot, as seen on the code.


