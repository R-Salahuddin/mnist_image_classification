<h2> Image Classification with MNIST Dataset </h2>

This project demonstrates a simple image classification task using the MNIST dataset of handwritten digits (0-9). The project utilizes a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images.
<h3> Requirements </h3>

<ul>
<li> Python 3.6+</li>
<li> TensorFlow 2.0+</li>
<li> Keras</li>
<li> NumPy</li>
<li> Matplotlib</li>
</ul>

You can install the dependencies using the command:
pip install tensorflow keras numpy matplotlib


<h4> <li>mnist_image_classification.py:</li> </h4>The main Python script that contains the code to load the dataset, build the CNN model, train it, and make predictions.
<h4> <li>README.md:</li></h4>This documentation file.


<h3> Model </h3>
The model architecture consists of:

<li> 3 Convolutional Layers: These layers extract important features from the images. </li>
<li> 2 MaxPooling Layers: These reduce the spatial dimensions of the feature maps.</li>
<li> Fully Connected Layers: After flattening the output from the convolutional layers, fully connected layers are added for classification. </li>


<h3> Results </h3>
Once trained, the model is evaluated on the test set. The test accuracy should be around 99% after training for 5 epochs.
