# Denoising Dirty Document Images

This repository contains code and datasets used for the task of denoising dirty document images. The project employs a convolutional autoencoder model to enhance image quality, making it suitable for further processing and analysis.

## Project Overview

The dataset used for this project is based on a Kaggle competition. Due to file size restrictions on GitHub, I will upload the three zip files contained within the main dataset zip file individually. The competition link can be found [here](https://www.kaggle.com/competitions/denoising-dirty-documents/data).

The primary objective of this project is to build a robust convolutional autoencoder model that can effectively denoise images, facilitating better readability and interpretation of the documents.

## Repository Structure

```
/denoising-dirty-documents
│
├── /train.zip               # Dirty images used for training
├── /train_cleaned.zip       # Cleaned images used for training
├── /test.zip                # Test images to make predictions
├── DenoisingCAE.ipynb       # Jupyter notebook used for the process.
```

## Acknowledgements

Special thanks to Kaggle for providing the dataset, and to the open-source community for the resources and libraries that made this project possible.
