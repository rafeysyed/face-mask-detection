# Face Mask Detection

## Introduction
During the COVID-19 pandemic, wearing face masks has become a crucial measure to prevent the spread of the virus. In response to this, the development of deep learning models for detecting faces with and without masks has gained significant attention. This project focuses on creating a model for face mask detection trained on a dataset containing 7553 images with 3 color channels (RGB).

## Dataset
The dataset consists of 7553 RGB images divided into two folders: `with_mask` and `without_mask`. Images are named with labels indicating whether the person in the image is wearing a mask or not. There are 3725 images of faces with masks and 3828 images of faces without masks.

### Dataset Link
[Dataset Link](#https://www.kaggle.com/datasets/omkargurav/face-mask-dataset) (Replace with actual link)

## Model Performance
- Custom CNN Architecture:
  - Training Accuracy: 94%
  - Validation Accuracy: 96%
  
- ResNet Model:
  - Accuracy: 71%
  
- VGG19 Model:
  - Accuracy: 91%

## Preprocessing
The dataset was preprocessed by resizing the images, converting them to RGB scale, and scaling the image arrays.

## Model Building
Several models were built and trained for face mask detection, including a custom CNN architecture, ResNet model, and VGG19 model. Each model achieved varying levels of accuracy on the validation set.

## Conclusion
In conclusion, this project demonstrates the development of deep learning models for face mask detection, which can be useful for monitoring compliance with mask-wearing guidelines in various settings.

## Future Work
Future work may involve further fine-tuning the models to improve accuracy, collecting additional data to enhance model performance, and deploying the model in real-world scenarios for practical use.

---
Note: Please replace `[Dataset Link](#)` with the actual link to the dataset.
