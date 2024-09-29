# Storm
Prediction of Storm tracks using hybrid model


 Objective: 
 
The primary objective of this project is to leverage machine learning algorithms to predict the trajectories of storms. Accurate storm forecasting is essential due to the significant impact storms have on human lives and property.

 Data Collection: 
 
The data for this project was sourced from the India Meteorological Department (IMD) in Pune. The dataset included various meteorological features such as date, highest and lowest temperatures, surface pressure, dew point temperature, and relative humidity.

 Methodology: 
 
1.	Data Pre-Processing: 
Essential pre-processing steps were applied to clean and prepare the data for analysis.

3.	Learning Models:  
Multiple machine learning models were employed, including:
	Support Vector Machine (SVM)
	Random Forest Regressor
	Recurrent Neural Network (RNN)
	Decision Tree Regressor
	Ensemble Model (Voting Regressor)
	Hybrid Model

4.  Hybrid Model Development:
   The hybrid model combined the best features of the individual models to enhance prediction accuracy. The hybrid model is the combination of Kriging model and Random forest which is a combination of surrogate model with machine learning model to obtain more accurate result.

5. Results: 
 
The performance of the models was evaluated using mean squared error (MSE) and R-squared values:
- The hybrid model achieved the lowest MSE of 0.46, indicating superior prediction accuracy.
- The hybrid model also recorded the highest R-squared value of 0.95, explaining 95% of the variance in the data.
- The random forest regressor and ensemble model also performed well, with R-squared values of 0.80 and 0.74, respectively.

6. Conclusion:

The hybrid model emerged as the top performer, demonstrating the ability to accurately capture underlying patterns in the data and generate precise forecasts. The project highlights the effectiveness of hybrid models and ensemble approaches in improving prediction accuracy for storm trajectories.

7. Significance:
   
This project showcases the application of advanced machine learning techniques in meteorological forecasting, emphasizing the importance of integrating multiple models to achieve high predictive accuracy. The findings are crucial for disaster management and preparedness, potentially saving lives and reducing property damage.


