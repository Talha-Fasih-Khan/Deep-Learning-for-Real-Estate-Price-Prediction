# Deep-Learning-for-Real-Estate-Price-Prediction

#### -- Project Status: [Completed]

## Project Intro/Objective
The purpose of this project is to develop a model that can accurately estimate house prices based on various features. 

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* Python
* Pandas, jupyter
* etc. 

## Project Description
* Data
  * The dataset used for this study consists of real estate sale prices in King County, USA, and includes attributes such as the number of bedrooms, bathrooms, square footage, condition, location, and more. Also, two different model architectures were utilized in this case study. The initial model consisted of five dense layers with varying numbers of neurons. The final architecture included three dense layers with 10 neurons each, followed by an output layer with one neuron for price prediction. The activation function used was ReLU for the hidden layers and linear for the output layer.
    
* Data Preprocessing
   * To prepare the data for training the neural networks, a subset of relevant features was selected, including 'bedrooms', 'bathrooms', 'sqft_living', 'sqft_lot', 'floors', 'sqft_above', and 'sqft_basement'. Additionally, the target variable, 'price', was reshaped and scaled to facilitate processing.
     
* Model Architecture 
   * Two different model architectures were utilized in this case study. The initial model consisted of five dense layers with varying numbers of neurons. The final architecture included three dense layers with 10 neurons each, followed by an output layer with one neuron for price prediction. The activation function used was ReLU for the hidden layers and linear for the output layer.
     
* Model Training 
   * Both models were trained using the Adam optimizer and the mean squared error (MSE) loss function. The training process involved splitting the dataset into training and testing sets. The first model was trained for 100 epochs, while the second model was trained for the same number of epochs with a batch size of 50. The evaluation metrics, such as RMSE, MSE, MAE, R2, and Adjusted R2, were used to assess the model's performance.

## Deliverables
* [Deep Learning for Real Estate Price Prediction (Slide Deck)](https://docs.google.com/presentation/d/1VmePbSQIDRemlnL8zFzFpYDnv2jLQSyL18b-60pRH7w/edit?usp=sharing)

* [Deep Learning for Real Estate Price Prediction (Notebook)](https://github.com/Talha-Fasih-Khan/Deep-Learning-for-Real-Estate-Price-Prediction/blob/44df85fb05c8027bf268930e19a84439e1700aea/Deep%20Learning%20for%20Real%20Estate%20Price%20Prediction.ipynb)
