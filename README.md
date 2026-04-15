# Cat vs Eagle CNN

[![alt text](https://img.shields.io/badge/python-3.12%20-%20orange.svg)
[![alt text](https://img.shields.io/badge/tensorflow-2.10.0%20-%20blue.svg)
[![alt text](https://img.shields.io/badge/matplotlib-3.10.0%20-%20brightgreen.svg)
[![alt text](https://img.shields.io/badge/pillow-11.3.0%20-%20violet.svg)


This project is a comparison of the features extracted from images of a cat and an eagle using a convolutional neural network (CNN). The features are visualized to show the differences in the features extracted from the two images.

The two ipynb files, `cat_using_CNN.ipynb` and `eagle_using_CNN.ipynb`, contain code that loads the images, normalizes them, and then uses a pre-trained VGG16 model to extract features from the images. The features are then visualized using matplotlib.

To run the cat and eagle ipynb files:

1. Open a terminal and navigate to the directory where the ipynb files are located.
2. Install the required packages by running `pip install -r requirements.txt`
3. Run the cat ipynb file by running `jupyter notebook cat_using_CNN.ipynb`
4. Run the eagle ipynb file by running `jupyter notebook eagle_using_CNN.ipynb`
5. Follow the instructions in the ipynb files to execute the code.

