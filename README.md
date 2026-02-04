### Laboratory Work 1 — Image Classification (https://colab.research.google.com/drive/15GnvmaFcyCjXqwkGi7c7lHg_ptFs2YLb?usp=sharing)
### Questions 
1. **What is the Fashion MNIST dataset?**
   The Fashion MNIST dataset is a collection of grayscale images representing different types of clothing such as shirts, trousers, shoes, and bags. It contains 60,000 training images and 10,000 test images, with each image sized 28×28 pixels and classified into one of 10 categories.

2. **Why do we normalize image pixel values before training?**
   Image pixel values are normalized before training to scale them into a smaller range, usually between 0 and 1. This makes training faster, improves numerical stability, and helps the neural network learn patterns more effectively.

3. **List the layers used in the neural network and their functions.**
   The neural network uses a Flatten layer to convert the 2D image into a 1D array, a Dense hidden layer to learn features from the input data, and a Dense output layer with a softmax function to produce class probabilities for prediction.

4. **What does an epoch mean in model training?**
   An epoch refers to one complete pass of the entire training dataset through the neural network. During each epoch, the model updates its weights to improve performance and reduce error.

5. **Compare the predicted label and actual label for the first test image.**
   The predicted label for the first test image matches the actual label, indicating that the model correctly classified the image, for example identifying it as an ankle boot.

6. **What could be done to improve the model’s accuracy?**
   The model’s accuracy can be improved by increasing the number of training epochs, adding more layers or neurons, using convolutional neural networks, or applying regularization techniques such as dropout.
