# Module--Challenge-14

## Machine Learning Trading Bot

Assumeing the role of a financial advisor at a top five global financial advisory firms. 

## Instructions:

#### Establish a Baseline Performance

### Step 1: Import the OHLCV dataset into a Pandas DataFrame.

<img width="181" alt="image" src="https://user-images.githubusercontent.com/105945472/187036860-4b2ae019-0c8c-4c63-a870-8a1502221845.png">
 
### Step 2: Generate trading signals using short- and long-window SMA values.

<img width="209" alt="image" src="https://user-images.githubusercontent.com/105945472/187012070-073b8007-3f53-40ec-8a48-842bcfc2cbae.png">

<img width="209" alt="image" src="https://user-images.githubusercontent.com/105945472/187038564-0ea2c7e8-f524-4acf-bee2-85fbfb9d54f5.png">

### Step 3: Split the data into training and testing datasets.

<img width="137" alt="image" src="https://user-images.githubusercontent.com/105945472/187012132-7d483d05-03d1-44f8-bb6c-a79b3382badb.png">

### Step 4: Use the SVC classifier model from SKLearn's support vector machine (SVM) learning method to fit the training data and make predictions based on the testing data. Review the predictions.

<img width="181" alt="image" src="https://user-images.githubusercontent.com/105945472/187012201-ba58677f-25c7-4daa-ad4b-0c510735b004.png">

### Step 5: Review the classification report associated with the SVC model predictions.

<img width="204" alt="image" src="https://user-images.githubusercontent.com/105945472/187036891-18e3df85-1719-4c50-aeda-4cff8ee9cbe5.png">

### Step 6: Create a predictions DataFrame that contains columns for “Predicted” values, “Actual Returns”, and “Strategy Returns”.

<img width="221" alt="image" src="https://user-images.githubusercontent.com/105945472/187012286-16ef3059-620e-4d11-ba06-75fd97434893.png">

### Step 7: Create a cumulative return plot that shows the actual returns vs. the strategy returns. Save a PNG image of this plot. This will serve as a baseline against which to compare the effects of tuning the trading algorithm.

<img width="368" alt="image" src="https://user-images.githubusercontent.com/105945472/187036918-f2299c87-daf4-48e4-a96c-ab0bd9b8d4ef.png">

## Tune the Baseline Trading Algorithm
### Step 6: Use an Alternative ML Model and Evaluate Strategy Returns

### Step 1: Tune the training algorithm by adjusting the size of the training dataset.
<img width="374" alt="image" src="https://user-images.githubusercontent.com/105945472/187038165-2dc5d305-f8ac-421f-9a2d-6705e6829d12.png">

## Conculsion 
-There was not much of a noticeable change from a 3mth period to a 6mth period. 

### Step 2: Tune the trading algorithm by adjusting the SMA input features. 
<img width="206" alt="image" src="https://user-images.githubusercontent.com/105945472/187038655-06b75837-20aa-47d3-85a0-c124cebe8eab.png">

## Conculsion 
-The results from adjusting the windows algroithm did not have a noticeable change. 

### Step 3: Choose the set of parameters that best improved the trading algorithm returns. 

<img width="414" alt="image" src="https://user-images.githubusercontent.com/105945472/187039032-cd08c200-2771-4124-bbff-be42962c387e.png">

## Conculsion 
-From my anaylisis no tradiging paramerter was better at improving the algorithmic returns.

## Evaluate a New Machine Learning Classifier
<img width="390" alt="image" src="https://user-images.githubusercontent.com/105945472/187040262-1daf06fe-eede-47d1-a275-5d8a9657ddb3.png">
