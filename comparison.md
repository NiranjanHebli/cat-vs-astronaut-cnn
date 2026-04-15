# CNN Output Comparison: Cats vs Eagle Image

This project compares the output of a Convolutional Neural Network (CNN) on two images from the `skimage` library: a cat image and an eagle image. The CNN, specifically the `Conv2D` layer, captures distinct feature hierarchies in both cases. 

For the cat image, the model emphasizes fur texture, edges, and facial structures like eyes and whiskers. In contrast, the eagle image activates features related to feather texture, beak contours, and background contrast. 
The difference highlights how CNNs adaptively learn domain-specific spatial patterns.

Additionally, using the `VGG16` model, we can visualize the feature maps of the two images. The VGG16 model is a pre-trained model that has been trained on the ImageNet dataset and provides a set of pre-trained filters that can be used to extract features from images. 

By analyzing the feature maps, we can infer the hierarchy of features that are important for the model to recognize the cat and eagle images. For the cat image, the feature maps highlight the importance of fur texture and facial features such as eyes and whiskers. For the eagle image, the feature maps highlight the importance of feather texture, beak contours, and background contrast.

