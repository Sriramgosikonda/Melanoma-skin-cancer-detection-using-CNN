# Melanoma-skin-cancer-detection-using-CNN


## Overview
This project focuses on detecting Melanoma skin cancer using a Convolutional Neural Network (CNN). Melanoma is one of the deadliest forms of skin cancer, and early detection is crucial for effective treatment. By utilizing deep learning techniques, this project aims to classify skin lesions into various categories, including melanoma, using a custom-trained CNN model.

## Project Structure
- **Dataset**: The dataset used in this project contains images of skin lesions categorized into different classes such as actinic keratosis, basal cell carcinoma, dermatofibroma, melanoma, nevus, pigmented benign keratosis, seborrheic keratosis, squamous cell carcinoma, and vascular lesions. The dataset is sourced from ISIC (International Skin Imaging Collaboration).
- **Model**: A Sequential CNN model with 5 layers was trained for 20 epochs using Keras. The model was saved in the 'saved_model' folder with the `.h5` extension.
- **Prediction**: The trained model can predict the class of a given skin lesion image.

## Files in the Repository
- `train.py`: Script to train the CNN model.
- `predict.py`: Script to predict the class of a given skin lesion image using the trained model.
- `model.h5`: The saved trained model.
- `README.md`: This file provides an overview of the project.
- `requirements.txt`: Lists the required Python packages to run the project.

## Installation and Setup
1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/melanoma-skin-cancer-detection.git
    cd melanoma-skin-cancer-detection
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the dataset**: Place your dataset in the directory:
    ```
    [/content/gdrive/MyDrive/Skin cancer ISIC The International Skin Imaging Collaboration](https://drive.google.com/file/d/1xLfSQUGDl8ezNNbUkpuHOYvSpTyxVhCs/view?usp=drive_link)
    ```

## Training the Model
To train the model, run the following command:
```bash
python train.py
