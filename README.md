# DJIA Stocks TimeSeries Prediction

- This is a real time project that used to predicts the DJIA Stocks in the year of 2017.
- The Stocks contains few tickers that were in 2017.
- Created the model using TensorFlow and Keras.
- Dataset has taken from Kaggle.
- The model is built with LSTM's and Conv1D and made some twists to get best accuracy.

# Code and Libraries used

Python Version - 3.7

IDE - Google Collaboratory

Packages - Pandas, Numpy, Matplotlib, Plotly, Seaborn, TensorFlow, Keras

# Dataset
- Date	
- Open	
- High	
- Low	
- Close	
- Volume	
- Name

# Data Cleaning
- Finded missing values in one column
- Dropping Unnecessary columns from dataset

# EDA

![qd](https://user-images.githubusercontent.com/40689141/118129119-695fcc00-b419-11eb-9389-84fb88e19240.png)
![dwm](https://user-images.githubusercontent.com/40689141/118129124-6a90f900-b419-11eb-88b1-266f088e3b9d.png)

# Model Building

First, Started splitting data into train and validation.

Created a Windowed dataset, so that data gets inputs and targets

Forecast using Helper Function

Imported Some essential libaries to train our model

And our model is trained on LSTM, Bidirectional and some dense layers using tensorflow

Mainly, I'm training our model based on learning rate & super cool loss function called "Huber" with "mae" metrics.

Using Conv1D we could get some features to identify by our model, later using LSTM's the model get trained too good.

# Model Performances

mae: 6.9674

![dwF](https://user-images.githubusercontent.com/40689141/118129644-0f133b00-b41a-11eb-9882-f87f51a08880.png)

Note: Don't miss this amazing model, definetly u miss something without checking it out.

Keep in Touch !! https://www.linkedin.com/in/akshithkumar-05/
