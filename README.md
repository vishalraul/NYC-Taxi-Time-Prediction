# NYC Taxi Time Prediction

The dataset is based on the 2016 NYC Yellow Cab trip record data made available in Big Query on Google Cloud Platform. The data was originally published by the NYC Taxi and Limousine Commission (TLC). The data was sampled and cleaned for the purposes of this project. Based on individual trip attributes, you should predict the duration of each trip in the test set.

# Data Summary

* Data Set Name :- NYC Taxi Data.csv 

* Statistics – 
Rows - 1458644 
Features - 11 (Including Target) 
Target – Trip Duration Important 


* Columns:- 
	‘id’,  'vendor_id',   'pickupdate_time',   'dropoff_datetime',  	'passenger_count',  'pickup_longitude',   'pickup_latitude',  		'dropoff_longitude',  'dropoff_latitude',   'store_and_fwdflag', 	'trip_duration’.
  
# Data fields  
● id - a unique identifier for each trip

● vendor_id - a code indicating the provider associated with the trip record

● pickup_datetime - date and time when the meter was engaged

● dropoff_datetime - date and time when the meter was disengaged

● passenger_count - the number of passengers in the vehicle (driver entered value)

● pickup_longitude - the longitude where the meter was engaged

● pickup_latitude - the latitude where the meter was engaged

● dropoff_longitude - the longitude where the meter was disengaged

● dropoff_latitude - the latitude where the meter was disengaged

● store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip

● trip_duration - duration of the trip in seconds

# Steps to approach the problem
**Data Preprocessing and Finding Useful Features**

1. Preprocess the data if required.
2. Find out the useful featured from the dataset.
3. Get new features from the existing data and see how they correlate and what new information they provide us.
4. Remove the redundand data that does not provides us with any new information.

**Split data into training, test and validation sets**

 1.Split the dataset with all new features into train/test/validation sets.

2. Optionally, randomly shuffle the features so as to avoid overfitting.

**Choose a Machine Learning Model**

1. Choose a machine learning model and see that how that fits to the data.
2. Once the model performs well, check that if adding/subtracting any feature increases accuracy of the model.

**Final Model Visualization**

1. Create a Flask page or post on the blog about the approach with visualizations.
2. Make a Dashboard using "Tableau" and show visualizations from the data.

# Objective

# Build a model that predicts the total trip duration of taxi trips in New York City.
