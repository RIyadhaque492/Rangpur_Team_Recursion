What exactly does it do?

As we know DSCOVR occasionally behaves quirky, which isn’t a good sign for us.

So, we collected data(plasma dataset) and then we follow 3 steps:

Data Cleaning: We removed columns that don’t have values more than 80%.
Missing value plotting we visualise it after and before cleaning for better understanding.
Imputation: As we see, the value of every row’s deviation is not high. We applied a basic model and median for the rest of the data we applied Mean imputation ,Mode imputation ,Median Imputation and  KNN. The first steps will remove noise and distortions from the dataset. Then we calculated speed, density, and temperature from corrected spectral data.
Then we aligned the Kp-Index column to the dataset. IMF speed, density as input, and Kp will be our model’s output.


How does it work?

We used long short time(LSTM). Because LSTM sequence of features. Our project makes use of sequence models to catch magnetic and proton behavior through the time period.
We also applied GRU Model and got better accuracy than LSTM. Which is almost 83%.  




What do you hope to achieve?

Our project has great results in a reduction of noise, and distortions from datasets of DSCOVR. Which is almost 85% accurate. We are getting Total RMSE 13.51% and by mode imputation and GRU model we got a good accuracy of Kp



Also, in terms of predicting geomagnetic storms, we are getting 86% accuracy.



Additionally, we have designed a mobile application to forecast geomagnetic storms and other vice versa space weather events. We o collect NASA/NOAA API and according value of space weather events. Our app will send precautions and warning through SMS, and social media.



Tools, Hardware: Google Colab , Acer E 14 (Ram -4GB, Rom -1TB)

Language: Python for machine learning

React JS for WebApp

 To view our app please click https://www.figma.com/file/fsImtHVjzrHHagYeRE68En/team-recursion?type=design&node-id=209%3A208&mode=design&t=GfXwzQAhZrf7aJRV-1
 For Web Application https://geomag-gaurd.vercel.app/

