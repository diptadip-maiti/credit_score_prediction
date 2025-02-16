- **RFE** with **Random Forest Classifier** and **SelectKBest** with **f_classif** as score_func is used in feature selection.
- **RANDOM FOREST CLASSIFIER** is the best performing Algorithm with following hyperpatameters.
  ```
  rfc = RandomForestClassifier(
                             class_weight= 'balanced',
                             bootstrap = True,
                             ccp_alpha = 0.0,
                             criterion = 'gini',
                             max_depth = None,
                             max_features = 'sqrt',
                             max_leaf_nodes = None,
                             max_samples = None,
                             min_impurity_decrease = 0.0,
                             min_samples_leaf = 1,
                             min_samples_split = 2,
                             min_weight_fraction_leaf = 0.0,
                             n_estimators = 100,
                             n_jobs = None,
                             oob_score = False,
                             random_state = None,
                             verbose = 0,
                             warm_start = False)
- **Suppoer Vector Machine** is the second best performing algorithm.
