# Rock-Paper-Scissors Image Classification

This repository contains a deep learning model created using TensorFlow for classifying images of rock, paper, and scissors. The model is implemented in a Jupyter Notebook for ease of understanding and experimentation.

## Model Architecture

The model is structured as a Sequential model, with layers stacked on top of each other in a specified sequence. It comprises multiple Conv2D and MaxPooling2D layers, followed by a Flatten layer and two Dense layers.

## Optimization and Loss

The model utilizes Adam as the optimizer and categorical crossentropy as the loss function. Adam is an optimization algorithm that serves as an alternative to the standard stochastic gradient descent procedure for iteratively updating network weights based on training data. Categorical crossentropy is the chosen loss function for multi-class classification problems.

## Training Data

Training the model involves using an image generator, which pulls images from the specified directory, applies various image augmentations (such as rotation, shear, and horizontal flip), and feeds these augmented images to the model in batches.

## Prediction

Once the model is trained, you can upload an image, and the model will predict whether the image represents rock, paper, or scissors.

## Evaluation

During training, the model is also evaluated on validation data. This process helps assess how well the model performs on data it has not seen before.

**Note**: This model is designed specifically for classifying images of rock, paper, and scissors and may not perform optimally on images outside of this scope.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

Feel free to experiment with the model and adapt it for your own projects. If you encounter any issues or have suggestions for improvement, please open an issue.
