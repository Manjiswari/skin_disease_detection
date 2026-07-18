# Skin Disease Detection using CNN

## Overview
This project is a deep learning-based skin disease detection system that classifies skin diseases from medical images using a Convolutional Neural Network (CNN). It aims to assist in the early identification of skin conditions by providing accurate and automated image classification. The project includes image preprocessing, model training, evaluation, and prediction. It demonstrates the practical application of artificial intelligence in healthcare.

## Features
- Image preprocessing and augmentation
- CNN-based skin disease classification
- Model training and evaluation
- Predicts skin disease from input images
- Simple and easy-to-use interface

## Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

## Project Structure
```
skin_disease_detection/
│── dataset/
│── models/
│── notebooks/
│── app.py
│── train.py
│── predict.py
│── requirements.txt
│── README.md
```

## Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/skin_disease_detection.git
```

2. Navigate to the project directory
```bash
cd skin_disease_detection
```

3. Install dependencies
```bash
pip install -r requirements.txt
```

## Usage

### Train the Model
```bash
python train.py
```

### Predict on an Image
```bash
python predict.py
```

## Dataset
Use a publicly available skin disease image dataset (such as Kaggle or ISIC) and place it inside the `dataset/` folder before training.

## Results
The CNN model is trained to classify skin diseases from images with high accuracy. Performance can be further improved using data augmentation, transfer learning, and hyperparameter tuning.

## Future Improvements
- Deploy the model as a web application using Flask or FastAPI
- Support additional skin disease categories
- Improve accuracy using transfer learning (ResNet, EfficientNet)
- Add real-time image prediction

## License
This project is licensed under the MIT License.
