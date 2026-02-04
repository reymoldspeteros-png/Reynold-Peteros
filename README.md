### Laboratory Work 1 — Image Classification (https://colab.research.google.com/drive/15GnvmaFcyCjXqwkGi7c7lHg_ptFs2YLb?usp=sharing)
### Questions 1. What is the Fashion MNIST dataset?
The Fashion MNIST dataset is a collection of grayscale images of clothing items such as shirts, shoes, and bags.
It contains 60,000 training images and 10,000 test images.
Each image is 28×28 pixels and belongs to one of 10 fashion categories.

2. Why do we normalize image pixel values before training?
Normalization scales pixel values to a small range (usually 0 to 1).
This helps the neural network train faster and more efficiently.
It also improves numerical stability and overall model performance.

3. List the layers used in the neural network and their functions.

Flatten layer: Converts the 2D image into a 1D array.

Dense (hidden) layer: Learns patterns and features from the data.

Dense (output) layer with Softmax: Outputs probabilities for each class and makes the final prediction.

4. What does an epoch mean in model training?
An epoch is one complete pass of the entire training dataset through the model.
During each epoch, the model updates its weights.
More epochs generally help the model learn better, up to a point.

5. Compare the predicted label and actual label for the first test image.
The predicted label and the actual label for the first test image are the same.
This means the model correctly classified the image.
For example, both may be labeled as Ankle boot.

6. What could be done to improve the model’s accuracy?

Add more hidden layers or neurons.

Train for more epochs.

Use a convolutional neural network (CNN).

Apply regularization techniques like dropout.
