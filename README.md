# ML-Based-Analysis-of-Protein-Therapies-for-Down-Syndrome-in-Mice

Implemented models for binary and multiclass classification to evaluate the effectiveness of protein types in treating Down's Syndrome in mice.
Conducted thorough data cleaning, handled null values, eliminated irrelevant columns, and prepared the dataset for analysis.
Conducted EDA to gain insights into the dataset, identifying patterns, trends, and potential outliers.
Removed columns based on variance to enhance the quality of the dataset.
Plotted the correlation matrix after elimination based on null values and variance.
Eliminated features based on correlation to avoid multicollinearity.
Evaluated the distribution of classes to ensure a balanced dataset.
Implemented multivariate feature imputation techniques to handle missing variables.
Assessed model performance using accuracy, F1 score, balanced accuracy, and AUC.
Replaced NaN values with the mean of the respective column.

Implemented the following machine learning models:
1. Linear SVM with regularization as a hyperparameter.
2. RBF kernel SVM with kernel width and regularization as hyperparameters.
3. Neural network with a single ReLU hidden layer and Softmax output (hyperparameters: number of neurons, weight decay).
4. Random forest with max tree depth and max number of variables per node.

Checked feature importance for each model to identify crucial proteins.
Evaluated if systematically removing some features improved model performance (i.e., using recursive feature elimination).
Trained multiple models and selected the most effective one based on evaluation metrics.
Plotted the number of features vs. cross-validation scores to visualize model performance.
