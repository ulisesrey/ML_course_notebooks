# Machine Learning Course
This repository contains some exercices I solved with Machine Learning tools during the Machine Learning course at the Data Science Master at UOC.

## 1. Data Processing, balancing for LDA
### 1.1
### 1.2 NASA SkyRocket failure detection using imblearn and LDA
In this project we used the dataset `Turbo_engine.csv` to predict Rocket failure from the NASA Dataset. Since the dataset is unbalanced for the category we want to predict (failure), we used the imblearn library to balance our dataset. The idea is that without balancing our data, a model never predicting failure would have very high accuracy, because failure happens very, very rarely. However, when failure happens the consequences are dramatic, so we want to build a classifier that would detect all of them. Different data balancing methods (Random, SMOTE, ADASYN) were evaluated with a simple LDA (Linear Discrimination Analysis) to determine best strategy to detect Rocket Failure.
[Link to notebook](engine_failure_prediction/engine_failure_prediction.ipynb)/[html](engine_failure_prediction/engine_failure_prediction.html)

Tools: [LDA](https://scikit-learn.org/stable/modules/generated/sklearn.discriminant_analysis.LinearDiscriminantAnalysis.html), [Data Augmentation](https://en.wikipedia.org/wiki/Data_augmentation), [imblearn](https://imbalanced-learn.org/stable/), [Oversampling](https://imbalanced-learn.org/stable/over_sampling.html), [Random Oversampling](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.RandomOverSampler.html), [SMOTE](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.SMOTE.html), [ADASYN](https://imbalanced-learn.org/stable/references/generated/imblearn.over_sampling.ADASYN.html)


## 2.
## 3.
## 4.


Note: This repository contains the final version of the exercises. The cimmit history of the progress is in a private repository.
