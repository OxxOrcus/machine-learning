# Transfer Learning with Cats vs. Dogs

This project demonstrates the application of transfer learning using a pre-trained VGG16 model to classify images of cats and dogs.

## Description

The goal of this project is to build an image classifier that can accurately distinguish between cats and dogs. We will use a small dataset of images and leverage the power of transfer learning to achieve high accuracy with limited data.

The process involves:
1. Loading the VGG16 model pre-trained on the ImageNet dataset.
2. Removing the original classification layer.
3. Adding a new classification layer tailored for our binary (cats vs. dogs) classification task.
4. Freezing the weights of the pre-trained layers.
5. Training the new classification layer on our dataset.

## Dataset

The dataset used for this project is the "Cats vs Dogs" dataset.

It contains two folders, `Cat` and `Dog`, with images for each class.

## Requirements

- Python 3
- Keras
- TensorFlow
- Matplotlib
- NumPy

You can install the dependencies using pip:
```bash
pip install tensorflow keras matplotlib numpy
```

## Usage

1. The dataset is already included in the `PetImages` directory.
2. Run the `transfer_learning_cats_vs_dogs.ipynb` notebook to train the model and see the results.

## Results

After training, the model should achieve a high accuracy in classifying cats and dogs.

*(Screenshots will be added to the `/images` folder later)*
