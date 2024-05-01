The project consists of several key components:

Data Collection: The system utilizes the MNIST dataset, a popular benchmark dataset in the field of machine learning, which contains a large number of grayscale images of handwritten digits (0-9). 
Additionally, it allows for the integration of custom datasets, which we created using "paint" containing handwritten digit images.

Preprocessing: Image processing techniques such as reshaping, resizing, normalization, and noise reduction are applied to the digit images to standardize their format and enhance their quality. 
Preprocessing plays a crucial role in preparing the data for input to the deep learning models.

Model Training: Deep learning models, such as convolutional neural networks (CNNs) and SVM, are trained on the preprocessed MNIST digit images and custom made images respectively to learn 
meaningful representations and patterns. 
The models are optimized using training algorithms such as stochastic gradient descent (SGD) or Adam to minimize classification errors.
