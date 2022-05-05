**Machine Learning** technique (learning from examples and patterns matching) is used to map input (data) into output (labels) and figure out the patterns in the data. It ultilized the neural network (a network of artificial neurons) approach. The equation is $y=W*x + b$. 
- An artificial neuron is a mathematical function that takes in inputs and parameters and calculates an output. The power of neural networks results from a vast number of artificial neurons networked together.
- Computer start finding the paramters of weights and biases by initialized randomly and calculating the set of guess values and the correspondings error, which will then being averaged. In this case, you are calculating the *loss* for your model. And then the parameters are fine-tuning together, so that the accurate prediction equations can be obtained by considering the calculated loss value. By *trial-and-error* iteratively, the model gets closer to the true values. The whole process is known as the *learning process*. 
- Once the machine has arrived at the optimal parameters, it can be tested by providing an input value that it has not been trained on and evaluating the accuracy of the output.
- Based on the Learning Steps, we can conclude that machines learn by figuring out a pattern or a relationship by guessing the parameters, calculating the loss, and using this information to generate new and better guesses. 

<img src="Single Artificial Neurons.png" alt="Artificial Neuron" />

---
**What is Machine Learning?**
1. Make a guess
2. Measure the accuracy to the *target* value using the *loss* or *cost* function
    - *Mean Square Error* for error +- signs ignore
3. Optimize your guess (optimization using *optimizer* function)
4. Repeat to make a new guess
- the lower the loss value, the higher the accuracy of your model

The process of descending along the loss curve to reach the point of minimum error is called Gradient Descent.

<img src="Gradient Descend.png" alt="Gradient Descent" />

**Learning rate**
The size of this step is determined by the learning rate, which the programmer usually sets. If the learning rate is too low, it will take too long to reach the minimum. On the other hand, if the size of the step is too large, the value might overshoot the minimum!

**Gradient Descent**
During optimization, the model’s algorithm looks at the slope of the loss or cost function calculated at a point in time. The parameters (W and B) are adjusted based on the slope or gradient of the cost function curve (plotted on the y-axis with the parameters on the x-axis). The net result of this tuning is that the cost function descends in the direction of the minimum possible cost value. This optimization calculation is called gradient descent and involves the use of calculus.

**Training Set**
The training set refers to the portion of data you use when making your guess, measuring the loss, and using calculus to move down the curve to make a more accurate guess. The model uses the training set to find the optimal parameters W and B that minimize the cost or loss for the model’s prediction.

**Validation Set**
Validation data refers to the portion of data that the computer doesn’t use when calculating the guess or the loss but uses as a test during each iteration to see how the model performs on data that wasn’t used to train it. AI practitioners monitor this to see how well the model is training. If the accuracy and loss are widely different between these sets of data, then something is wrong.

**Testing Set**
The testing set is the portion of data used to gauge a model’s final accuracy. Unlike the training data, which has labeled inputs (the actual outputs are provided for each input for each example), the testing data inputs do not have labels or outputs. This is data that a model has never seen and is used as a final test for the model.

---
**Neurons**
In reality, what is referred to as a neuron here is simply a function that has two learnable parameters, called weight and a bias, where the output of the neuron will be:

***Output = (Weight * Input) + Bias***

- When multiple neurons work together in layers, the learned weights and biases across these layers can then have the effect of letting the neural network learn more complex patterns.

---
**What is Deep Learning?**: It is a machine learning technique involving artificial neurons arranged in networks consisting of multiple layers such that learning happens across each layer and in each neuron.

**Artificial Neural Network**: A network of connected neurons, arranged in vertical groups called layers, in which information flows in one direction from input to output.

**Machine Learning** is a process of using lots of mathematics to figure out the parameters to a function

**Dense Neural Network** is implying there is a lot of learning in between the layers, and it refers to the weights line in-between those neurons layers. The larger the dataset or the more complex the things need to be achived, the larger the hidden layers need to use for deep learning purpose. Deep Neural Network is just repeating what is done and the looping figure across all the neurons to ensure the correct answer is being obtained. Hence, each neural network has its own weights and biases value. (A type of neural network in which a layer's neurons are connected to every neuron of the next layer.)

<img src="Artificial Neural Netwrok.png" alt="Dense Network" />

**One-hot Encoding**: data is labeled using one-hot-encoding to label classes using 1s or 0s. 

<img src="Dense Neural Network.png" alt="Dense Artificual Neural Network" />

- The repetition is for each and every neuron in the dense artificual neural network. 

**Application of Computer Vision (Machine Learning)**
1. Air Cognizer
2. Crop Disease Detection
3. Diabetic Retinopathy Detector