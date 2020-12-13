# 3D_Metal_Printing

This is the foundation of an image classification program for a 3D metal printer.
The image classification uses convolutional neurual network (CNN) models implemented with Tensorflow and Keras.

All images used are contained in compressed .tar.gz files in this repository.

The program uses 2 different CNN models, the first to detect errors and the second to classifify the error type.
Due to limited data available Data augmentation has to be used prevent overfitting of the models.
