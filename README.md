# Hotel-Demand-Analysis

Analyzed the hotel demand data set and predicted the likelikhood of cancellations. Further, used the predictions to estimate the true demand that would show up.

# Business Problem and Importance
The hotel demand stems from business travelers and leisure tourists who travel frequently. With information on the hotel bookings, our goal is to predict booking cancellation. The business questions we are trying to answer are:
1) Would a customer cancel his booking?
2) If yes, what are the driving factors of cancellations?
3) What is the effect of cancellations on the demand?

Predicting hotel demand is useful in allocating staff to cover the front desk, restaurant, and cleaning. In addition to that, knowing the expected hotel demand helps to estimate the demand of subsidiary businesses like gift shops, gyms and spas that are housed in hotels.
With the increase in flexible cancellation policy through online services, estimating the cancellation rates becomes important so that the hotel is not left with spare rooms to sell at a lower rate. Also, the optimal overbooking rate for the hotel with seasonality in mind could be derived by understanding the expected cancellation rate. So, predicting the likelihood of cancellation feeds into the demand analysis of the hotel in the considered period.

# Data set
The data we worked on is the hotel demand dataset on Kaggle that contains information on two types of hotel, the resort and city hotel.
https://www.kaggle.com/jessemostipak/hotel-booking-demand

# Approach
1) Started with exploratory data analysis and data pre-processing that included missing value imputation, Feature Engineering, reduce multi-collinearity and handle class imbalance
2) Conducted feature selection using Recursive Feature Elimination
3) Used Machin elearning models to predict the likelihood of cancellation
4) Used the predictions of the best model to estimate the demand

# Findings and Recommendations

Studying the results of best model and the inferences we got using the feature importance values, we recommend the following to hotel business owners.

1) Get the expected number of cancellations on a day from the model and use it to calculate the overbooking limit that would give the highest returns considering the capacity, booking limit and penalty to pay in case a room cannot be provided to a customer.

2) Realize the true demand for the day using the cancellation model, demand calculations and plan staffing and other supplies accordingly to serve customers.

3) This information could be used by the owners to realize the expected demand in the peak and off-peak seasons and plan their marketing strategies accordingly.

4) Room type changes reduces the probability of cancellation. So, if the hotel is not fully occupied, offer upgrades to customers. This reduces the likelihood of cancellation and ensures a part of the revenue is realized.

5) Total number of special requests reduces the likelihood of cancellation. So, being flexible on offerings seems to encourage customers to stay. Knowing the true demand, which now can be calculated from our models would help us accommodate these requests.
