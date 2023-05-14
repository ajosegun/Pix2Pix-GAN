## Pix2Pix GAN - Image-to-Image Translation

This project is a implementation of the Pix2Pix GAN for image-to-image translation. The Pix2Pix GAN is a conditional generative adversarial network that can be used to translate images from one domain to another. For example, you could use the Pix2Pix GAN to translate real celebrites images to their cartoonized version, or from sketches of products to photographs of products.

## Technologies

| Technology   | Description                                                               |
|--------------|---------------------------------------------------------------------------|
| Python       | An interpreted, high-level programming language used for general-purpose programming. |
| NumPy        | A popular Python library used for scientific computing and working with arrays. |
| Keras       | A  a high-level API that makes it easy to build and train neural networks. |
| TensorFlow | An open-source software library for numerical computation using data flow graphs. |


## Getting Started
To get started with this project, you will need to have the following installed:

Python 3.6 or higher

NumPy

TensorFlow

Keras

## Installation
Once you have installed the necessary dependencies, you can clone the project repository from GitHub:

```
git clone https://github.com/ajosegun/pix2pix-gan.git
```

The code is divided into 4 notebooks.
1. 00_Pix2Pix_GAN_for_Image_to_Image_Translation_Cartoonize_Images.ipynb
  Collect a dataset of Celebrity pictures and generated a complete ground truth ⇒ paired images (real <> cartoonized) (train and test) using a script (opencv) to stylish images. 
  
2. 01_Pix2Pix_GAN_for_Image_to_Image_Translation_Preparing_Dataset.ipynb
  Here, feature engineering is perfomed on the dataset to transform it into a form usable by the model.
  
3. 02_Pix2Pix_GAN_for_Image_to_Image_Translation_Modeling.ipynb
  This builds the Pix2Pix GAN Model. This model learn to map input images to output images, in our case real to non-real.
  
4. 03_Pix2Pix_GAN_for_Image_to_Image_Translation_Testing.ipynb 
  Here, we test the model on new images.


## Conclusion
The Pix2Pix GAN is a powerful tool for image-to-image translation. With this model, you can translate images from one domain to another, such as from daytime to nighttime, or from sketches to photographs. The model is easy to use and can be trained on a variety of different datasets.






