# Image Segmentation and Classification

This project implements image segmentation and classification using a U-Net model and a custom classification model. The goal is to accurately segment images into different classes and classify them accordingly. 

## Project Overview

The project consists of the following components:

1. **Data Preparation**: The images and corresponding masks are loaded from the provided dataset. The images are preprocessed, including gamma correction, and converted to RGB format. The masks are one-hot encoded based on a specified colormap.

2. **U-Net Model**: The U-Net architecture is used for image segmentation. The model is trained on the prepared data to segment the images into different classes based on the provided masks.

3. **Custom Classification Model**: A custom classification model is implemented to classify the segmented images into specific classes. The model is trained on the segmented images to perform classification.

4. **Evaluation**: Various evaluation metrics, such as confusion matrix and accuracy score, are used to assess the performance of the segmentation and classification models.

## Usage

1. **Data Preparation**: Run the `Prepare_Data` class to load and preprocess the images and masks. Specify the image and mask paths accordingly. Adjust the gamma correction and color conversion as needed.

2. **Model Training**: Train the U-Net model for image segmentation and the custom classification model for classification. Specify the model architectures, loss functions, optimizers, and other hyperparameters. Use the prepared data for training.

3. **Model Evaluation**: Evaluate the performance of the trained models using appropriate evaluation metrics. Generate and visualize the confusion matrix to assess the classification accuracy.

## Dependencies

The project requires the following dependencies:

- Python (version 3.11.22)
- OpenCV (version 4.7.0)
- NumPy (version 1.23.5)
- Matplotlib (version 37.1)
- Scikit-learn (version 1.2.2)
- TensorFlow (version 2.12.0)
- Keras (version 2.12.0)

## Dataset

The project uses a provided dataset containing images and corresponding masks. The dataset should be placed in the specified directories (image_path and mask_path) before running the code.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- This project is inspired by the U-Net architecture for image segmentation.
- The provided dataset is sourced from https://drive.google.com/drive/folders/14DtM2x4UfIQR0au6LDARSb8YaLuagczJ?usp=sharing.

