# Fruit-Classifier
A project that uses TensorFlow machine learning to classify images of various fruits. 

## To view the project, simply click on "Fruit Classifier.ipynb" in the Github repository which should open an html version in your browser, or clone the repository and launch the notebook yourself.

## Project Features:
1. Builds multiple ConvNets with varying parameters and explores the performance and parameter differences between each.
    - Achieves up to \~98% training accuracy and \~86% test accuracy using these basic models
2. Explores a few transfer learning solutions using Google's InceptionV3 model as well as Oxford's VGG16 model.
    - Achieves up to \~99.8% training accuracy and \~90.5% test accuracy using these models
3. Evaluates the precision of these models against a small sample of hand-picked images from the real world (which contain very different image resolutions, environments, camera quality etc.) 
    - Can models trained using this dataset be effectively trained for use in the real world? 