<h1>Face Mask Detection System</h1>

<h2>Overview</h2>

The Face Mask Detection System is a cutting-edge application designed to enhance public health and safety measures by utilizing advanced machine learning and computer vision technologies. By leveraging TensorFlow, Keras, and OpenCV, this system is capable of accurately detecting the presence of face masks on individuals in real-time. The project aims to contribute to the ongoing efforts in managing public health, especially in settings where wearing a face mask is mandatory or recommended.

<h2>Features</h2>

<h4>Real-Time Face Mask Detection:</h4> Utilizes a trained machine learning model to detect face masks on individuals in real-time with high accuracy.
<h4>Color-Coded Feedback:</h4> Provides immediate visual feedback; a green overlay indicates a mask is properly worn, while a red overlay signals the absence of a mask or incorrect wearing.
<h4>Advanced Machine Learning Model:</h4> Employs a sophisticated convolutional neural network (CNN) trained on a large dataset of images with and without face masks to ensure reliable detection.
<h4>Face Detection:</h4> Integrates OpenCV's face detection capabilities to first identify the presence of a face before assessing mask status.

<h2>Technology Stack</h2>

<h4>TensorFlow & Keras:</h4> Used for building and training the machine learning model.
<h4>OpenCV:</h4> Facilitates real-time video processing and face detection.
<h4>Python:</h4> The primary programming language for developing the application.

<h2>Dataset</h2>

The model is trained on a diverse dataset comprising thousands of images categorized into two classes: 'With Mask' and 'Without Mask'. This dataset ensures that the model can accurately identify the mask status under various conditions and across different face types.

<h2>Prerequisites</h2>

<ol>
  <li>Python 3.6 or later</li>
  <li>TensorFlow 2.x</li>
  <li>Keras</li>
  <li>OpenCV</li>
</ol>

<h2>How It Works</h2>

<h4>Face Detection:</h4> 
Upon starting, the application uses OpenCV to capture live video feed and detect faces in real-time.
<h4>Mask Detection:</h4>
For each detected face, the TensorFlow and Keras powered model predicts the presence of a mask, providing a probability score for accuracy.
<h4>Visual Feedback:</h4>
Depending on the prediction, the application overlays a green rectangle for faces with masks and a red rectangle for those without masks or improperly worn masks.

