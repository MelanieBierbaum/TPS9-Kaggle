# TPS9-Kaggle

Jupyter Notebooks for the Kaggle competition: Tabular Playground Series September 2021

About the competition:

The dataset is used for this competition is synthetic, but based on a real dataset and generated using a CTGAN. The original dataset deals with predicting whether a claim will be made on an insurance policy. Although the features are anonymized, they have properties relating to real-world features.

Type: Binary Classification

Evaluation Metric: Area under the ROC curve (AUC)

My repository contains the following notebooks:

* tps9-eda-comparison-train-test-set.ipynb
  * Exploratory Data Analysis with focus on comparing train and test set
* tps-9-different-data-transformations.ipynb
  * exploring visually how different data transformation techniques affect the feature distributions 
* tps9-how-to-transform-your-data.ipynb
  * running LightGBM with differently preprocessed data and comparison of the results
* tps-9-model.ipynb
  * Optuna tuned LightGBM

* tps9-lightgbm-s-optuna-integration.ipynb
  * using Optunas LightGMB Tuner for (faster) sequential hyperparameter tuning
