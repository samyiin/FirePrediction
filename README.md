# Fire Prediction Project
The project takes a similar data to the kaggel "188 million US wildfire" dataset, and predicts the cause of fire. The model I select is XGBoost. The final result is in the notebook "FirePrediction.ipynb". 
## Data source
Since the dataset are too large to upload to git, I will provide a link to download this data, and all the axillary data that is used in running the notebook.  
https://drive.google.com/drive/folders/1BvbpLbhGZh7IRwlFxdf569blXJgJ6oyd?usp=sharing
## How to run
Place "data.csv" and "storm_events.csv" that you downloaded from above link, place them under a the same directory as the notebook, 'FirePrediction.ipynb'.
Also make sure you have an empty directory named "tempFiles". Then you are good to go.  
The entire notebook takes about 15 minutes to run on CPU, and 10 minutes on T4GPU. I recommend using google collab (and then you will need to change the csv file directories).
## About the project
In this project I used various exploratory data analysis and feature engineering techniques, I also includes all the previous failed attempts. Worth checking it out. They are run on google collab, so the file system might be a bit different. But it shouldn't be too hard to understand. 
And after the feature engineering and feature selections, I perform experiments on CatBoost, XGboost, Random Forest and decision tree. The first three models are preforming equally well. 
