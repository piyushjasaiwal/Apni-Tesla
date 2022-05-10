# Apni-Tesla 
## A Simple Approach to Problem of Self Driving Car

The project aims to train a Convunational Neural Network so that for a given a set of images. The Model should predict the angle of the steering wheel to continue driving safely. The angle must be predicted in such a way that it minimizes the RMSE(root mean squared error) between what the model predicts and actual angle predicted by the human driver. 

## Insights of the Machine Learning Model

- The machine learning model used in project is basic CNN i.e., a convolutional neural network
- The various layers used in the CNN are flatten, Dense and Dropout. 
- We have used rectified linear activation unit function or relu as the activation function in the hidden layers. The activation function used in the output layers is tanh.
- The purpose of adding dropout layers was to add regularization and prevent overfitting.

- The Loss function we have used RMSE i.e. mean Squared error

- For the optimization part, we have used the Adam Optimizer.

## Results

The model once trained on the training dataset has been tested on the testing dataset which is the 20% of the original dataset. The model runs smoothly on the testing dataset with a loss of only 0.0521%.


### Steering angle Prediction on a Straight Road

![alt text](https://github.com/piyushjasaiwal/Apni-Tesla/blob/main/images/straight.png?raw=true)

### Steering angle Prediction on a Curved Road

![alt text](https://github.com/piyushjasaiwal/Apni-Tesla/blob/main/images/curved.png?raw=true)