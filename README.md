<h1>Neural Network Architectures and Training with Keras</h1>

<h2>Overview</h2>
<p>
This project explores the implementation and training of neural networks using
<strong>TensorFlow and Keras</strong>.
</p>

<p>
It covers both classification and regression tasks while experimenting with multiple Keras model-building approaches:
</p>

<ul>
  <li>Sequential API</li>
  <li>Functional API</li>
  <li>Multi-input and Multi-output models</li>
  <li>Wide and Deep architecture</li>
  <li>Model subclassing</li>
  <li>Custom callbacks</li>
  <li>TensorBoard integration</li>
</ul>

<p>
The objective of this project is to understand how neural networks are structured, trained, evaluated, and extended in practical deep learning workflows.
</p>

<hr>

<h2>Datasets Used</h2>

<h3>Fashion MNIST (Classification)</h3>
<ul>
  <li><strong>Task:</strong> Multi-class image classification</li>
  <li><strong>Input:</strong> 28x28 grayscale clothing images</li>
  <li><strong>Output:</strong> 10 clothing categories</li>
  <li><strong>Loss Function:</strong> Sparse Categorical Crossentropy</li>
  <li><strong>Metric:</strong> Accuracy</li>
</ul>

<p>
A fully connected neural network was implemented with hidden layers and a softmax output layer.
</p>

<h3>California Housing (Regression)</h3>
<ul>
  <li><strong>Task:</strong> Predict median house value</li>
  <li><strong>Input:</strong> Numerical housing features</li>
  <li><strong>Output:</strong> Continuous price value</li>
  <li><strong>Loss Function:</strong> Mean Squared Error (MSE)</li>
</ul>

<p>
Feature scaling was applied using StandardScaler before training regression models.
</p>

<hr>

<h2>Architectures Implemented</h2>

<h3>Sequential Model</h3>
<ul>
  <li>Dense hidden layers with ReLU activation</li>
  <li>Softmax output for classification</li>
  <li>Linear output for regression</li>
</ul>

<h3>Functional API Model</h3>
<ul>
  <li>Custom model graphs</li>
  <li>Input concatenation</li>
  <li>Flexible architecture design</li>
</ul>

<h3>Wide and Deep Model</h3>
<ul>
  <li>Combined raw input features (wide path)</li>
  <li>Deep neural network layers</li>
  <li>Feature concatenation before final prediction</li>
</ul>

<h3>Multi-Input Model</h3>
<ul>
  <li>Separate input branches</li>
  <li>Merged representations</li>
</ul>

<h3>Multi-Output Model</h3>
<ul>
  <li>Main output and auxiliary output</li>
  <li>Custom loss weighting</li>
</ul>

<h3>Subclassed Model</h3>
<ul>
  <li>Custom class inheriting from keras.Model</li>
  <li>Overridden call() method</li>
  <li>Explicit control over forward pass</li>
</ul>

<hr>

<h2>Training Techniques</h2>
<ul>
  <li>Train, validation, and test split</li>
  <li>Feature normalization and scaling</li>
  <li>Model compilation with different loss functions</li>
  <li>Model evaluation on unseen test data</li>
  <li>Probability prediction and class decoding</li>
  <li>Saving and loading trained models</li>
  <li>Custom Keras callbacks</li>
  <li>TensorBoard logging for visualization</li>
</ul>

<hr>

<h2>Results</h2>
<ul>
  <li>Strong validation accuracy on Fashion MNIST classification</li>
  <li>Successful regression predictions for housing prices</li>
  <li>Demonstrated architectural flexibility using multiple Keras APIs</li>
  <li>Implemented training monitoring using callbacks and TensorBoard</li>
</ul>

<hr>

<h2>Project Structure</h2>

<pre>
neural_network_architectures_keras.ipynb
README.md
requirements.txt
</pre>

<hr>

<h2>Requirements</h2>
<ul>
  <li>Python 3.x</li>
  <li>TensorFlow</li>
  <li>NumPy</li>
  <li>Pandas</li>
  <li>Matplotlib</li>
  <li>Scikit-learn</li>
</ul>

<p>Install dependencies using:</p>

<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2>Key Learning Outcomes</h2>
<ul>
  <li>Understanding differences between Sequential, Functional, and Subclassing APIs</li>
  <li>Designing multi-input and multi-output neural networks</li>
  <li>Combining shallow and deep model components</li>
  <li>Managing weighted losses in multi-output training</li>
  <li>Monitoring and controlling training with callbacks</li>
  <li>Saving, reloading, and evaluating trained models</li>
</ul>
