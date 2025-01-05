# Wine-Quality-Prediction-model
Train the model to predict the quality of the wine (red and white wines) Using regression.By this The wine Producers ,sellers etc can easily identify the Quality of wine with the help of this model

**Overview of Problem Statement:**

The wine industry is a multibillion-dollar market, with quality assessment and classification of paramount importance in establishing the price, consumer preference, and ultimately market success. Historically, wine quality is rated by human experts by using sensory analysis. Even though this is of significant value, it remains subjective in nature, very time-consuming, and also very expensive. This necessitates an objective, consistent, and efficient method of predicting the quality and characteristics of wine.This method would bring consistency, transparency, and scalability to the evaluation of wines, therefore helping producers, sellers, and consumers alike.

**Objective:**
Eg: To develop the best Wine quality prediction model using machine learning techniques.

**Data Description:**
- Source: From UCI:- https://archive.ics.uci.edu/dataset/186/wine+quality
- Features:
fixed_acidity,
volatile_acidity,
citric_acid,
residual_sugar,
chlorides,
free_sulfur_dioxide,
total_sulfur_dioxide,
density,
pH,
sulphates,
alcohol,
quality,
Wine_type(red or white after combaining both changed to 0 as white and 1 as red )

**Conclusion**

This Model is to predict the Quality of Wine Based on the Chemical Properties of wine like PH, citric acid, free sulfur dioxide, fixed acidity, alcohol, etc.The performance of the Model Depends on the features selected and data preprocessing and the Algorithms choose. from the models that we tested, we got the best performance was from the random forest regression, which has a higher degree of accuracy and r2 score. From this model, the wine producers and stakeholders can make data driven decisions to improve the quality control and can make quality checking cost effective and get Customer satisfaction
