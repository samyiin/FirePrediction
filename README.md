# Fire Prediction Project
The project takes a similar data to the kaggel "188 million US wildfire" dataset, and predicts the cause of fire. The model I select is XGBoost.
## Data source
Since the dataset are too large to upload to git, I will provide a link to download this data, and all the axillary data that is used in running the notebook.  
https://drive.google.com/drive/folders/1BvbpLbhGZh7IRwlFxdf569blXJgJ6oyd?usp=sharing
## How to run
Place "data.csv" and "storm_events.csv" that you downloaded from above link, place them under a directory named "trainingData/".
Also make sure you have directory named "savedFiles/" and "savedModel/". Then you are good to go.  
The entire notebook takes about 15 minutes to run on CPU, and 10 minutes on T4GPU. I recommend using google collab. 
## About the project
In this project I used various exploratory data analysis and feature engineering techniques, I also includes all the failed attempts of mine. Worth checking it out. 
