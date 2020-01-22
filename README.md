# <center> <font color='green'> Machine Learning Application
# <center> Predicting the Market Value of FIFA football players
    
# <center>![FIFA 2019](http://www.blogproductreview.com/wp-content/uploads/2018/10/download-6.jpeg)
    
    
The "fifa19" dataset used here can be downloaded from [Kaggle](https://www.kaggle.com/karangadiya/fifa19)

# Contents  
#### I. Data exploration  
    1. Data processing  
    2. Data visualization  
#### II. Information reduction  
    1. Outliers Detection
    2. Ridge and Lasso Regression 
    3. Variance Inflation Factor (VIF)  
    4. Principal Component Analysis (PCA)  
#### III. Linear regression  
    1. Cost Function  
    2. Gradient computing  
    3. Stochastic gradient descent  
    4. Scipy minimze function
    5. OLS regression from statsmodels
    6. Linear polynomiale Regression
#### IV. Tree-based Methods (NonLinear Algorithms)
    1. Variables Importances: Features Selection  
    2. Regression Trees
        2.1. Choose the best criteria and depth
        2.2. Train and evaluate the model using the best criterion and optimal depth
        2.3. Decision Tree Plot
        2.4. Trying without max_depth
    3. Random forests Regression  
        2.1. Choose the best depth
        2.2. Train and evaluate using 10-folders of cross-validation
    4. Gradient Boosting for regression using 10-folders of cross-validation
    5. Bagging Regression
        5.1. Bagging using Scikit-Learn algorithm
        5.2. Bagging implementation From Scratch: manual implement
#### V. K-Nearest Neighbors (KNN) Regression
    1. Find the optimal K-NeighborsRegressor
        1.1. Find the optimal K using KNeighborsRegressor
        1.2. Find the optimal K using GridSearchCV
    2. K-Nearest Neighbors implementation
        2.1. K-Nearest Neighbors using Scikit-Learn Algorithms
        2.2. K-Nearest Neighbors (KNN) implementation From Scratch
#### VI. Support Vector Regression (SVR)  
    1. Find the optimal Penalty parameter C of the error term the option kernel
    2. Evaluate the performance using 10-Folders of Cross-Validation
#### VII. Unsupervised Learning   
    1. K-Means Clustering  
        1.1. Find the optimal clusters using K-Means Algorithm from Scikit-Learn
        1.2. K-Means Implementation From Scratch: manual implement
        1.3. Test the K-Means Implementation function using two variables
        1.4. Aplly the algorithm on the full dataset
        1.5. Buil a function that can reseach the players how have the same characteriscs with a give player
        1.6.  K-Means provided by the sklearn.cluster Algorithm
    2. Hierarchical Clustering: an alternative of K-Means  
    3. Principal Component Analysis (PCA) for clustering   
#### VIII. Neural Network architecture using tensorflow  
    1. Build a Neural Network(NN) the model
    2. Inspect theNeural Network model
    3. Train the Neural Network model
    4. Visualize the model's training progress using the stats stored in the history object
    5. Performe the Neural Network model in order to take in account the overfiting problem
    6. Evaluation of the Neural Network model
#### IX. Models Comparison: Which is the best one ?  
    1. Split the data using Cross-Validation of 10-foldres
    2. Run the models
    3. Comparaison using plot, MAE, MSE, Score, 
