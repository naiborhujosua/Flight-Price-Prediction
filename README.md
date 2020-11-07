<img src="http://cliparts.co/cliparts/6iy/oBb/6iyoBbdpT.gif"/>

### Flight-Price-Prediction

1. [Project Motivation](#motivation)
2. [File Descriptions](#files)
3. [Results](#results)
4. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Motivation<a name="motivation"></a>

I was interested in Flight Airfare Prediction listings to help tourists find the right flight airfare based on their needs.

## File Descriptions <a name="files"></a>

This Project is used to predict the flight prices. We will use Flight Price Dataset provided by Kaggle Flight Price. This dataset consists of 10683 records with 13 columns that explain about the flight in India by some Indian and foreign Airlines in 2019. We will analyze this dataset using Machine learning techniques in order to predict the flight ticket price based on the features provided in the columns of the dataset. We will begin the Data Science Life Cycle to process the data such as Cleaning the dataset, feature engineering, splitting dataset, feature selection, and hyperparameter tuning.

## Results<a name="results"></a>

The main findings of the code can be found at the post available on my medium [here](https://medium.com/@naiborhujosua/predicting-airfare-price-using-machine-learning-techniques-bf3a13ad07d1).

## 3. Modelling and Evaluation

* Algorithms used
  * Random Forest
  * Extra Trees Regressor


* Metric - Since the target variable is a continuous variable, regression evaluation metric RMSE (Root Mean Squared Error) and R2 Score (Coefficient of Determination) have been used.

## 4. Results

#### Feature correlation
![Feature correlation](https://github.com/naiborhujosua/Flight-Price-Prediction/blob/master/Feature_correlation.jpeg)
#### Feature importance
![Feature importance](https://github.com/naiborhujosua/Flight-Price-Prediction/blob/master/Feature_Importance.jpeg)
#### Accuracy before Hyperparameter Tuning
![Final Comparison](https://github.com/naiborhujosua/Flight-Price-Prediction/blob/master/accuracy_before_tuning.jpeg)
#### Accuracy After Hyperparameter Tuning
![Final Comparison](https://github.com/naiborhujosua/Flight-Price-Prediction/blob/master/accuracy_after_tuning.jpeg)

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Credited to Kaggle for availability of the data. You can find the License for the data and other descriptive information in the Kaggle available [here](https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh). Otherwise, feel free to use the code here as you would like! 
