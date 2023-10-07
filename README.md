# Rangpur_Team_Recursion
In this project, we proposed a data-processing method and machine learning pipeline to predict the space weather indicators. Additionally, we are proposing an app to alert people by accurate geomagnetic storm prediction we divide it into sub-problems of our solution.
Missing Value imputation
Predict the storm happening probability based on proton data. Each of the transforms uses a time sequence model to capture. The result will help to correct anomalies and success in predicting geomagnetic storms.

What exactly does it do?

As we know DSCOVR occasionally behaves quirky, which isn’t a good sign for us.
So, we collected data(plasma dataset) and then we follow 3 steps:
Data Cleaning: We removed columns that don’t have values more than 80%.
Missing value plotting we visualise it after and before cleaning for better understanding.
Imputation: As we see, the value of every row’s deviation is not high. We applied a basic model and median for the rest of the data we applied KNN. The first steps will remove noise and distortions from the dataset. Then we calculated speed, density, and temperature from corrected spectral data.
Then we aligned the Kp-Index column to the dataset. IMF speed, density as input, and Kp will be our model’s output.

How does it work?

We used long short time(LSTM). Because LSTM sequence of features. Our project makes use of sequence models to catch magnetic and proton behavior through the time period.

What do you hope to achieve?

Our project has great results in a reduction of noise, and distortions from datasets of DSCOVR. Which is almost 85% accurate. We are getting R^2–score 0.8571.
Also, in terms of predicting geomagnetic storms, we are getting 86% accuracy.

Additionally, we have designed a mobile application to forecast geomagnetic storms and other vice versa space weather events. We want to collect NASA/NOAA API according to the value of space weather events. Our app will send precautions and warnings through SMS, and social media.

Tools, Language, Hardware

Language:

Python for machine learning
React JS for App


##HOW TO RUN## 

We have provided the required data in the data folder of colab. So you have to change the datapath according to your operating system path. 
For the app please click on this link: https://www.figma.com/proto/fsImtHVjzrHHagYeRE68En/team-recursion
For the website: https://geomag-gaurd.vercel.app/
