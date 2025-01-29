# Tomato Disease Detection

Welcome to the **Tomato Disease Detection** project! This repository contains a Jupyter Notebook that demonstrates the implementation of a deep learning model for classifying tomato leaf diseases based on image data.

## Overview
Tomato crops are highly susceptible to various diseases, which can impact yield and quality. This project uses machine learning and deep learning techniques to identify different types of tomato leaf diseases from images. The model processes input images and predicts the corresponding disease class.

## Project Structure
The repository is organized as follows:

- **Dataset**: Contains images of tomato leaves labeled with different diseases.
- **Preprocessing**: Image augmentation and preprocessing steps.
- **Model Training**: Implementation of a CNN model using TensorFlow/Keras.
- **Evaluation**: Model performance analysis and accuracy metrics.

## Dataset
The project utilizes a dataset of tomato leaf images classified into different disease categories, such as:

- Healthy
- Early Blight
- Late Blight
- Leaf Mold
- Septoria Leaf Spot
- Bacterial Spot
- Yellow Leaf Curl Virus
- Mosaic Virus

Each image undergoes preprocessing before being used for model training.

## Implementation
The **R_Tomato_Disease_Code.ipynb** notebook walks through the following steps:

1. **Data Preprocessing**: Loading and augmenting image data using `ImageDataGenerator`.
2. **Feature Extraction**: Converting images into numerical representations.
3. **Model Training**: Implementing a CNN model using Keras.
4. **Model Evaluation**: Measuring performance using accuracy and loss metrics.
5. **Prediction & Visualization**: Displaying sample predictions and performance graphs.

## Installation & Execution
To run this project locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/Tomato-Disease-Detection.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Tomato-Disease-Detection
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open and run **R_Tomato_Disease_Code.ipynb**.

## Results
The trained model successfully classifies tomato leaf diseases with high accuracy. Performance is visualized using loss and accuracy plots, along with confusion matrices.

## Contributing
Contributions are welcome! If you have improvements, fork the repository and submit a pull request.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it.

