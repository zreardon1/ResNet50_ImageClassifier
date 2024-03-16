# ResNet50_ImageClassifier
This project is focused on transfer learning using the ResNet50 convolutional neural network. The objective was to fine tune a pretrained ResNet50 model to accurately classify images of 30 separate classes of balls (beach ball, meatball, soccer ball, etc.).

Directory
- images: This folder contains test, train, and eval sets with images of the different types of balls. The data was obtained from https://www.kaggle.com/datasets/gpiosenka/balls-image-classification.
- models: This folder houses the final trained model produced after training the initialized ResNet50 model on the training set.
- ResNet50_fine_tuned_image_classifier.ipynb: This Jupyter Notebook includes the code used for loading, processing, and visualizing the project data, as well as training, generating, and assessing the final fine tuned model.
