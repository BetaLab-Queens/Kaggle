# Kaggle - Categorical Feature Encoding Challenge II
Repo for the Kaggle Data Science Team 

[![Nbview](https://github.com/jupyter/design/blob/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/BetaLab-Queens/kaggle)

![](https://storage.googleapis.com/kaggle-media/competitions/playground/cat_in_dat/cat7.jpg)

[The Competition](https://www.kaggle.com/c/cat-in-the-dat-ii/overview)

__Evaluated on__: Area under ROC

__Models used:__
- Random Forest Classifier
- LightGBM Classifier
- CatBoost Classifier
- XGboost Classifier
- Fastai Tabular
- Ensembling by taking the mean of all predictions

__Encodings Used used:__
- Binary Encoding
- Target Encoding
- Ordinal Encoding
- Embedding Layer


__Results__:

| Model                              | Private Leaderboard | Public Leaderboard|
|------------------------------------|---------------------|-------------------|
| Random Forest Classifier           |0.75538              |0.75701            |
| LightGBM Classifier                |0.77856              |0.77792            |
| XGboost Classifier                 |0.77859              |0.77672            |
| CatBoost Classifier                |0.78074              |0.77993            |
| Ensemble with all models           |0.78299              |0.78246            |
| Ensemble without random forest     |0.78515              |0.78385            |
| Fastai Tabular                     |0.78551              |0.78374            |
