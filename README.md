# dog-breed-classifier
CNN used to classify different types of Dog's breeds

Since Convolutional layers are used to abstract features from the images we used 3 or more hidden layers in order to 
get more complex features from the images.

The model designed inspired by VGG19 designed as "CONV-CONV-POOL" ordered.

After desired accuracy achieved on our own model , the transfer learning method is used to increase the accuracy.

Since PyTorch consists pretrained models , "AlexNET" called and used for transfer learning.

It is desired that our model can classify "133" different type of dog's breed , pretrained "AlexNET" model have been 
configured according to the output number.

All the weights and parameters kept same since we use the convolutional layers as feature extractor.
The last fully connected layer in original model configured.
The accuracy was way better than the designed model above.

Also , the face detector used which was pretrained as HAAR-FaceDetecor with extension ".html"
