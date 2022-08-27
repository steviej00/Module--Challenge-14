# Module--Challenge-14

## Machine Learning Trading Bot

Assumeing the role of a financial advisor at a top five global financial advisory firms. 

## Instructions:

### Establish a Baseline Performance

-Establish a Baseline Performance

### Step 1: Import the OHLCV dataset into a Pandas DataFrame.

	<img width="176" alt="image" src="https://user-images.githubusercontent.com/105945472/187012050-6744ffcc-8fa4-4510-a292-ee19388e56e3.png">

 
### Step 2: Generate trading signals using short- and long-window SMA values.

<img width="209" alt="image" src="https://user-images.githubusercontent.com/105945472/187012070-073b8007-3f53-40ec-8a48-842bcfc2cbae.png">

### Step 3: Split the data into training and testing datasets.

<img width="137" alt="image" src="https://user-images.githubusercontent.com/105945472/187012132-7d483d05-03d1-44f8-bb6c-a79b3382badb.png">

### Step 4: Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.

<img width="181" alt="image" src="https://user-images.githubusercontent.com/105945472/187012201-ba58677f-25c7-4daa-ad4b-0c510735b004.png">

### Step 5: Review the classification report associated with the SVC model predictions.

img width="209" alt="image" src="https://user-images.githubusercontent.com/105945472/187012225-f2efc35a-3117-44d2-a20d-ca4ef5d22bbb.png">

### Step 6: Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”.

<img width="221" alt="image" src="https://user-images.githubusercontent.com/105945472/187012286-16ef3059-620e-4d11-ba06-75fd97434893.png">
<img width="368" alt="image" src="https://user-images.githubusercontent.com/105945472/187012319-9c6f7615-2c6d-4eda-87de-aa7113cdcff4.png">

### Step 7: Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.

![Uploading image.png…]()

### Step 6: Use an Alternative ML Model and Evaluate Strategy Returns


