Since this assignment indicates ‘using keras’, we shall use TensorFlow. Therefore, we start by importing tensorflow development framework and the related fashion_mnist dataset.

Thereafter, we load our dataset, import the essential layers, preprocess the data and develop a CNN with the respective six layers to classify the Fashion MNIST dataset.

We have convolutional layers as well as additional ones to flatten, regularise and classify the data.

In addition, we train our model using the Adam Optimizer and test its accuracy after training to assess its performance. Our model was trained for 10 epochs, taking between 20 and 24 seconds for each, going through the 60,000 samples each time. 

During training, the model performed at 68.05%, but this improved with each epoch, whereas with an initial training loss of 86.14%, this reduced over time. The Model-Accuracy increases, and the Model-Loss decreases, as shown by the visualization summary, as the model gets to understands the data better. 

Since the Training-Accuracy and Validation-Accuracy are increasing above the 90% mark and the Training-Loss and Validation-Loss are decreasing to below 25%, the model demonstrates a good generalization.

We perform classification and realise an F1-score overall accuracy of 92 percent, which means that 92% of the predictions are correct across the ten classes. However, the model performs well in almost all classes except class 6, meaning it faces difficulty in identifying shirts.

Finally, we make predictions for at least two images from our Fashion MNIST dataset.
