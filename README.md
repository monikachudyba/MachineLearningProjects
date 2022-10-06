# Machine learning algorithms practise

## Classification Decision Trees
> Classification of the health of a fetus as Normal, Suspect or Pathological using Cardiotocograms data.
- data cleaning and exploration;
- Decision Tree hyperparameters adjustment;
- Decision Tree visualisation with *graphviz* and *dtreeviz*.
> Final accuracy: 92.40%

## Driving Behavior Dataset
> Classification of the driver behavior as Sudden Acceleration, Sudden Right Turn, Sudden Left Turn 
and Sudden Break using accelerometer and gyroscope data for development Advanced Driving Assistance Systems (ADAS) 
and Intelligent Transportation Systems (ITS).
- data cleaning and exploration;
- SVM hyperparameters adjustment and 2D results visualisation with PCA and *mlxtend.plotting*;
> Final accuracy: 99.42%
- Random Forest hyperparameters adjustment and 2D results visualisation with PCA and *mlxtend.plotting*;
> Final accuracy: 99.81%
- removing ouliers with UMAP and DBSCAN before XGBoost implementation;
- XGBoost hyperparameters adjustment and 2D results visualisation with PCA and *mlxtend.plotting*;
- *graphviz* visualisation of trees for one estimator.
> Final accuracy: 99.87%
- Naive Bayes classification: Gaussian, Multinomial and Complement.
> Final accuracy: 93.95%

## Regression - House Pricing
> Prediction of house sale prices for King County, Washington in USA in 2015. 
- data cleaning and exploration;
- interactive plot with *plotly* and *ipywidgets*;
- removing ouliers with Isolation Forest;
- Elastic Net hyperparameters adjustment and 3D results visualisation with Permutation Importance and *plotly*;
> Final coefficient of determination: 69.84%
- AdaBoost with different base estimators, hyperparameters tuning + 2D interactive plot visualisation with *plotly* and *ipywidgets*;
> Final coefficient of determination: 81.85%
- Bagging with different base estimators, hyperparameters tuning + 2D interactive plot visualisation with *plotly* and *ipywidgets*;
> Final coefficient of determination: 83.87%
