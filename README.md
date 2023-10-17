# Cat vs Dog Image Classifier

![Cat vs Dog](link_to_an_image.png) <!-- Add an image to represent your project -->

This repository contains a Python Jupyter Notebook (cat_vs_dog.ipynb) for a binary image classification task using Convolutional Neural Networks (CNNs) to distinguish between images of cats and dogs.

## Dataset

The dataset used for this project consists of 25,000 images, with 12,500 images of cats and 12,500 images of dogs. These images are divided into 10,000 training samples and 2,500 test samples for evaluation.

## Models

There are two different models implemented in this notebook, both using CNNs with approximately 11 layers, including Dense and Flatten layers. The primary activation function used is ReLU. Here's a summary of the models and their respective accuracies:

1. **Model 1:**
   - Accuracy: 88%
   - Number of layers: 11
   - Architecture: [Convolutional Layers, Pooling Layers, Dense (ReLU), Flatten, Dense (Sigmoid)]

2. **Model 2:**
   - Accuracy: 85%
   - Number of layers: 11
   - Architecture: [Convolutional Layers, Pooling Layers, Dense (ReLU), Flatten, Dense (Sigmoid)]

Detailed model architectures and hyperparameters can be found in the Jupyter Notebook.

## Usage

To use this project:

1. Clone this repository:

   ```shell
   git clone https://github.com/yourusername/cat_vs_dog.git

2. Open the Jupyter Notebook `cat_vs_dog.ipynb` in your Jupyter Notebook environment or use Google Colab.

3. Follow the step-by-step instructions in the notebook to train and evaluate the models.

4. You can also experiment with different hyperparameters or augment the dataset to improve model performance.

## Results

This project achieves an accuracy of 88% for Model 1 and 85% for Model 2. You can explore the trained models and evaluate their performance on the provided test dataset.

## License

This project is available under the [MIT License](LICENSE).

## Acknowledgments

We would like to thank the creators of the dataset used in this project for making it publicly available.

Feel free to reach out if you have any questions or suggestions!

Happy classifying cats and dogs!
```

Please replace `"link_to_an_image.png"` with the URL or relative path to an image that represents your project, and customize other details as needed. This README provides an overview of your project, the dataset, the models, usage instructions, and licensing information.
