## MNIST Autoencoder and Classifier

This repository contains a deep learning project for digit classification using a 2-stacked autoencoder and an artificial neural network (ANN) classifier. The project is implemented in a Jupyter Notebook.

## Open in Colab

You can open and run the notebook in Google Colab by clicking the button:
        [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([link_to_your_colab_notebook](https://colab.research.google.com/github/nagaditya39/Autoencoder-Classifier/blob/main/2Stacked_AE.ipynb))



## Description

The project consists of the following components:

1. **2-Stacked Autoencoder**:
   - The autoencoder is trained to reconstruct input images from the MNIST dataset. It consists of two stacked layers: an encoder layer that compresses the input images into a lower-dimensional representation, and a decoder layer that reconstructs the images from this representation.

2. **Feature Extraction**:
   - After training the autoencoder, the encoder layer is used to extract features from the input images. These features capture important information about the input images in a lower-dimensional space.

3. **Artificial Neural Network (ANN) Classifier**:
   - The extracted features are fed into a simple artificial neural network classifier. This classifier is trained to classify the MNIST digits based on the features extracted by the autoencoder.

4. **Evaluation**:
   - The performance of the autoencoder and the classifier is evaluated using metrics such as reconstruction loss for the autoencoder and accuracy for the classifier. The project also includes code to visualize the original images, reconstructed images, and the predicted labels for random samples from the MNIST dataset.


## Usage

1. Clone the repository:

   ```
   git clone https://github.com/nagaditya39/Autoencoder-Classifier.git
   ```

2. Open the notebook in Jupyter Notebook or Google Colab.

3. Run the cells in the notebook to train the autoencoder, extract features, train the classifier, and visualize the results.

## Requirements

Install the required packages using pip:

```
pip install pandas numpy tensorflow matplotlib
```



