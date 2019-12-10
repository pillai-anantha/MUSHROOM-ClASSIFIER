# MUSHROOM-ClASSIFIER
# Classify mushrooms as poisonous or non poisonous (R)

# Mushroom Classification.RMD

## Data Preparation

*Read data from 'mushrooms.csv'

*Remove variables with only 1 value and substitute bad values with NA

*MICE library with Polyreg method and LDA method to impute missing values from data

*LDA is preffered because of density pots

*Factorize all categorical variables, create one hot vectors

*Variable selection done using best subset, forward and backward selection. We move ahead with best subset selection

## Classification

*Constructed logistic, LDA, Decision Tree and Random forest models

*Found important variables from each model and noted it down with exploratory analysis in Final.Mushroom Classification.docx

*The Mushroom Classification.html is the knit version of the RMD file

*Presentation.pptx contains insights from the data exploration and models built

*Random forest with accuracy 100% was the best model
