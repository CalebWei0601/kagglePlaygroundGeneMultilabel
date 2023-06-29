# kagglePlaygroundGeneMultilabel

My second kaggle Data Analysis Project - on multilabelling of genes.

Given that the correlation between the two labels are low, I adopted the approach of creating a model for each of the two labels independently.

The model employed was XGBoost, and Optuna was used to finetune the relevant hyperparameters, along with sklearn for feature selection.
