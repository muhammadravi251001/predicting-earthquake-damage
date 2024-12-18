# predicting-earthquake-damage

The code is for predicting the severity of the impact of an earthquake on a building. Classification is performed through several experiments, including using models like Logistic Regression, SVM, XGBoost, Neural Networks, and Random Classifier; with the highest configuration search using Grid Search and Randomized Search; as well as based on the highest feature correlations (with an experimentally adjustable `THRESHOLD`) as the main predictor features of the model.

This code successfully achieved **third** place on the [public leaderboard](https://www.kaggle.com/competitions/ml-olympiad-predicting-earthquake-damage/leaderboard?tab=public) of the [ML Olympiad 2024](https://developers.googleblog.com/2024/04/ml-olympiad-2024-globally-distributed-ml-competitions-by-google-ml-community.html).

You can cite the olympiad/competition in:
```
@misc{ml-olympiad-predicting-earthquake-damage,
    author = {Tensor Girl},
    title = {ML Olympiad - Predicting Earthquake Damage},
    publisher = {Kaggle},
    year = {2024},
    url = {https://kaggle.com/competitions/ml-olympiad-predicting-earthquake-damage}
}
```
