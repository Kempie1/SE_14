# SE 14 - High Level Description - Artem Miroshnichenko

## Ai-stock-analysis
### Problem Description: 
Predict movement in the stock market
### Area of AI: 
Neural Networks
### Applied Algorithms: 
Neural network, and Recurrent Neural Network
### Results: 
The predictions using the recurrent neural network were quiet good. And after figuring out how to hook up my gpu to tenserflow, I was able run the model much faster.
### Location: 
stock_predictor.ipynb

----

## Traffic
### Problem Description: 
Train an AI model to recognize german traffic symbols from an image.
### Area of AI: 
Neural Networks
### Applied Algorithms: 
A convolutional neural network, that takes in an image, flattens it and runs it through the neural network.
### Results: 
Maximum accuracy I got was 96.56%, played around with different layers. Realized that my linear activation on the output was a horrible idea, and after switching to softmax, the model became way better.
### Location: 
traffic

