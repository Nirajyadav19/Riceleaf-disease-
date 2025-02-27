# Rice Leaf Disease Detection Project

## Project Overview
This project focuses on detecting diseases in rice leaves using Machine Learning and Deep Learning techniques. The model leverages image data to classify different types of diseases affecting rice plants, enabling early detection and better crop management.

## Dataset
The dataset consists of rice leaf images categorized into different disease classes. Each image is preprocessed to ensure uniformity before model training.

### Dataset Structure
- Healthy Leaves
- Brown Spot Disease
- Hispa Disease
- Leaf Blast Disease

## Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- Jupyter Notebook

## Model Architecture
The model is built using a Convolutional Neural Network (CNN) with the following layers:
1. Convolutional Layers
2. MaxPooling Layers
3. Fully Connected Layers
4. Softmax Output Layer

## Installation
### Prerequisites
- Python 3.x
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

### Setup
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd rice-leaf-disease-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the dataset.
2. Run the notebook:
   ```bash
   jupyter notebook Riceleaf_Disease.ipynb
   ```
3. The model will train and display results.

## Results
The model achieves an accuracy of 97.51% on the validation dataset.

## Future Improvements
- Data Augmentation
- Model Optimization
- Deployment using Flask API

## Contributors
- Niraj Yadav



