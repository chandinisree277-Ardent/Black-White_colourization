# Black-White_colourization
This Python script colorizes grayscale images using a pre-trained Caffe model. It loads the model, preprocesses the input image by converting it to LAB color space, and uses the neural network to predict the 'ab' color channels. Finally, it combines the original 'L' channel with the predicted 'ab' channels to create a colorized output.
