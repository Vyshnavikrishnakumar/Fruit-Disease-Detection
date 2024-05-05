 Fruit-Disease-Detection
The objective of fruit disease detection using image processing is to use digital images of fruits to identify and classify any diseases or abnormalities present on their surface. 
Fruit Infection Disease Detection using Convolutional Neural Networks

Overview

This project aims to develop a tool for detecting various types of fruit infections and diseases using Convolutional Neural Networks (CNNs). By leveraging deep learning techniques, we can analyze images of diseased fruits and accurately identify the specific type of infection or disease present.

 Dataset

The dataset used for training and testing the CNN model is carefully curated and organized. It contains a diverse collection of images showcasing different types of fruit diseases, including Angular Leaf Spot, Anthracnose Fruit Rot, Blossom Blight, and more. Each image is labeled with the corresponding disease category, ensuring comprehensive training data for the model.

 Requirements

To run the project, ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- OpenCV
- NumPy

You can install the required Python packages using pip:

bash
pip install -r requirements.txt


 Quick Start

1. Clone the Repository:

   bash
   git clone https://github.com/yourusername/fruit-disease-detection.git
   cd fruit-disease-detection
   

2. Train the Model:

   To train the CNN model on the dataset, run:

   bash
   python train_model.py
   

3. Detect Diseases:

   Once the model is trained, you can use it to detect diseases in input images. To do this, run:

   bash
   python detect_disease.py /path/to/input/image.jpg
   

   Replace /path/to/input/image.jpg with the path to your input image.

 Model Architecture

The CNN model architecture is designed to effectively learn and classify fruit disease patterns from images. It consists of multiple convolutional layers for feature extraction, followed by max-pooling layers to reduce spatial dimensions. The flattened output is then passed through fully connected layers to perform classification. The model is trained using the Adam optimizer and categorical cross-entropy loss function.

 Output

Upon detecting diseases in input images, the output consists of an annotated image with the predicted disease labels overlaid. This visual representation helps users identify the detected diseases easily.

 Example

To see the tool in action, follow these steps:

1. Ensure the model is trained using train_model.py.
2. Provide an input image containing a fruit with a suspected disease.
3. Run the disease detection script using detect_disease.py.

Experience the power of AI as it analyzes fruit images and assists in disease identification!
