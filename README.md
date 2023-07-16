# Wild_Fire_Detection_model
Introduction:

- This repository contains code for a wildfire detection model built using TensorFlow, a popular deep learning framework. The model is designed to detect the presence of 
 wildfires in satellite imagery with a high degree of accuracy. The model uses a combination of a pre-trained MobileNet and a custom convolutional neural network to achieve an 
 accuracy of 96% on the test dataset.

# Model Architecture:

The model architecture consists of a pre-trained MobileNet as a feature extractor, followed by several convolutional layers with ReLU activation and max-pooling layers to reduce the spatial dimensions of the feature maps. The final output of the model is a binary classification indicating whether or not a wildfire is present in the input image.

# Training:

The model was trained using transfer learning, where the pre-trained MobileNet was fine-tuned on the wildfire dataset. The model was trained using the Adam optimizer with a binary cross-entropy loss function. The model achieved an accuracy of 96% on the test dataset.
