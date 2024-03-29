# Alex_A_Portfolio
Portfolio of Data Science and Machine Learning Projects

## [Project #1: Comparing Statistical Algorithms for Spam Classification](https://github.com/aarbisman/spam_classification/blob/main/model_comparison.ipynb)

* Mitigates issues from the imbalanced dataset by employing Stratified K-fold Cross Validation and focusing on Recall during model fitting.

* Wrangles text data using TfIdf vectorization and creates additional features based off of message metadata.

* Compares Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, and AdaBoost models to find the best model for Spam Classification.

* Achieves a classification accuracy of 98.4% and a Recall of 99.7%

![Comparison of word distributions between spam and non-spam messages](images/word_dist_comparison.PNG)

Message size comparison for spam and legitimate messages.

## [Project #2: Modeling Home Appliance Energy Consumption](https://github.com/aarbisman/modeling_home_energy_usage/blob/main/modeling_energy_consumption.ipynb)

* Compares Modeling Techniques for a dataset with skewness, outliers, and low correlation of independant vs dependant variables.

* Examines statistical significance of categorical variables using T-tests and Anova.

* Employs Cross-Validated Hyperparameter Grid Searching and backwards selection to optimize models.

* Reduced Mean Squared Error by ~40% by employing an XGBoost model.

![Skew Comparison of Different Transformations](/images/skew_comparison.PNG)

Skew Comparison of Different Transformations

## [Project #3: Predicting UFC Match Outcomes](https://github.com/aarbisman/ufc_prediction/blob/master/ufc_prediction.ipynb)

* Examines a dataset from a sport with a high level of data variance.

* Utilizes null imputing/dropping, data scaling, and t-test based feature screening to preprocess Data.

* Employs Cross-Validated Hyperparameter Grid Searching accross three different models, spanning 8,000+ model fittings to find optimal hyperparameter set.

* Combines optimized models into an ensemble classification model to improve accuracy.

![visual t-test](/images/visual_t_test.png)

Visual interpretation of t-test used for feature screening


## [Project #4: Finding distinctions in DND monsters using clustering](https://github.com/aarbisman/dnd_monster_clustering/blob/main/clustering_basic_v1.ipynb)
* Attempts to find meaningful distinctions in high-variance, low observation count data.

* Compares centroid-based k-nearest neighbor clustering to hierarchical clustering algorithms in terms of making meaningful distinctions.

* Examines results of clustering algorithms using scatterplots.

![Entire dataset, clustered](/images/all_data_clustering_results.png)

Data clusters, visualized

## [Project #5: Creating an optimal fantasy hockey roster using a Dynamic programming algorithm](https://github.com/aarbisman/knappsack_nhl/blob/main/different_iterations_of_drafting_algorithm.ipynb)
* Sets up a daily fantasy draft like a modified version of a knapsack problem

* Solves this problem using dynamic programming algorithm, centered around a dictionary of nested lists.

* Adds features to this algorithm to make it compatible with DraftKings' daily fantasy draft.

![Optimized draft example](/images/optimized_draft_photo.PNG)

Optimized draft example


## [Project 6: Leveraging 538's baseball predictions for sports betting](https://github.com/aarbisman/leveraging_538_for_betting)

* Creates various web scraping scripts meant to be used on 538's baseball predictions and DraftKings' baseball money lines.

* Stores results in a relational database using SQLite.

* Creates an ETL script to transfer results into a data warehouse for analysis.

![Payout Comparison](/images/payout_comparison.PNG)

Payout Comparison
