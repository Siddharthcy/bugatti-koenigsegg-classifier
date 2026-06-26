# 🏎️ Bugatti vs Koenigsegg Classifier

An image classifier built with **fast.ai** and a pretrained **ResNet-18** model that classifies images into one of three categories:

- Bugatti
- Koenigsegg
- Other Cars

## Dataset

The dataset was created by:
- Downloading images using DuckDuckGo Search.
- Organizing images into separate class folders.
- Cleaning mislabeled images using `ImageClassifierCleaner`.
- Resizing images before training.

## Model

- ResNet-18 (Pretrained)
- Transfer Learning
- Fine-Tuning
- Multi-class Image Classification

## Results

- Validation Accuracy: **XX.XX%**
- Validation Error Rate: **XX.XX%**

## Sample Prediction

![Sample Prediction]<img width="187" height="184" alt="image" src="https://github.com/user-attachments/assets/921dca6b-0dff-4e6d-bbd2-7887e6faec7a" />


Prediction: **Bugatti Supercar**

- Bugatti: **63.06%**
- Koenigsegg: **33.59%**
- Other Car: **3.35%**

## Confusion Matrix

<img width="421" height="436" alt="image" src="https://github.com/user-attachments/assets/7f30ad03-bcea-440e-b3e0-c604bb518849" />


## Future Improvements

- Increase the dataset size.
- Improve dataset quality by removing mislabeled images.
- Add more hypercar manufacturers.
- Experiment with deeper architectures such as ResNet-50.
- Allow users to upload their own images for prediction.

## Technologies Used

- Python
- fast.ai
- PyTorch
- DDGS
- Google Colab
