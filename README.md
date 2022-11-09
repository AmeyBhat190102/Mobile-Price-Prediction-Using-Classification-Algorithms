# Mobile-Price-Prediction-Using-Classification-Algorithms

This Project is on the Dataset: Mobile Price Prediction Dataset 
Dataset Link: https://www.kaggle.com/code/vikramb/mobile-price-prediction/data

The Dataset has around 2000 rows and contains 21 columns. The different attributes that are present are:
[1] battery_power: Total energy a battery can store in one time measured in mAh
[2] blue: Has bluetooth or not
[3] clock_speed: speed at which microprocessor executes instructions
[4] dual_sim: Has dual sim support or not
[5] fc: Front Camera mega pixels
[6] four_g: Has 4G or not
[7] int_memory: Internal Memory in Gigabytes
[8] m_dep: Mobile Depth in cm
[9] mobile_wt: Weight of mobile phone
[10] n_cores: Number of cores of processor
[11] pc: Primary Camera mega pixel
[12] px_height: Pixel Resolution Height
[13] px_width: Pixel Resolution Width
[14] ram: RAM in Megabytes
[15] sc_h: Screen Height of mobile in cm
[16] sc_w: Screen Width of mobile in cm
[17] talk_time: longest time that a single battery charge will last when you are
[18] three_g: Has 3G or not
[19] touch_screen: Has touch screen or not
[20] wifi: Has wifi or not
[21] price_range: The Range of Price Of the particular Phone based on the independent variables

By The Help Of the Models that are trained in this particular project we will be able to predict the possible price range in which that particular Mobile Phone will belong and estimate the price of the phone accordingly. Also the customer will be able to see the specification that will be available for his budget of the customer.

The Models That have been applied are:
[1] Logistic Regression
[2] Decision Tree Classifier
[3] SVM Classifier
[4] XGBoost Classifier
[5] Random Forest Classifier
[6] Naive Bayes Classifier
[7] KNN Classifier

EDA was performed on the dataset and the results are available in the document uploaded

After checking for null values in the Dataset(here none were present) correlation between the attributes and the outcome variable were calculated to find if there are any corelated attributes amoung each other except the outcome variable. Later the highly corellated variable were dropped and models fitting was done on the dataset.

All the above mentioned models were trained and it was found that 

-> SVM Classifier : 95.4%
-> XGBoost Algorithm : 92.2%
-> KNN Classifier: 92%
-> Random Forest Classifier : 91%
-> Decision Tree Classifier : 84%
-> Naive Bayes Classifier : 80%
-> Logistic Regression : 63%

As we can see that the First 4 Algortihms had more than 90 percent Accuracy we further move on to Cross Validation of these models. The Results of Cross Validation are:

-> Cross Validated Accuracy Of SVM: 97.5%
-> Cross Validated Accuracy Of XGBoost Algorithm: 91.2%
-> Cross Validated Accuracy Of KNN Classifier: 92.5%
-> Cross Validated Accuracy Of Random Forest Classifier: 89%

From this we can conclude that the SVM Classfier has the most accurate prediction.

Predictions were made on the Testing Data On the basis on the SVM Model.

