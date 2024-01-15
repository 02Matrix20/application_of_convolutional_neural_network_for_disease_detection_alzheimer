# application-of-convolutional-neural-network-for-disease-detection-alzheimer
This code creates a graphical user interface (GUI) using the Tkinter library tools to train and test a neural network model on images.


Alzheimer's Disease Prediction
This repository contains a Python application for Alzheimer's disease prediction using a Convolutional Neural Network (CNN). The application provides a graphical user interface (GUI) built with Tkinter, allowing users to load datasets of healthy individuals and those with Alzheimer's disease, as well as a test dataset for evaluation. The CNN model is trained on the provided datasets, and predictions are displayed with corresponding test results.

Requirements
Ensure you have the following libraries installed before running the application:

os
numpy
tkinter
PIL (Pillow)
keras
scikit-learn
You can install these dependencies using the following command:

bash
Copy code
pip install numpy scikit-learn pillow keras
How to Use
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/alzheimers-disease-prediction.git
cd alzheimers-disease-prediction
Run the application:
bash
Copy code
python alzheimers_prediction_app.py
The GUI window will appear. Follow these steps:

a. Load the dataset of healthy individuals using the "Load Healthy Dataset" button.

b. Load the dataset of individuals with Alzheimer's disease using the "Load Alzheimer's Dataset" button.

c. Load the test images for evaluation using the "Load Test Images" button.

d. Click on the "Train and Test" button to initiate the training of the CNN model and display the test results.

View the status messages, test results, and predictions within the GUI.

Note
Ensure that the Pillow library (PIL) is installed. If not, you can install it using the following command:
bash
Copy code
pip install pillow
The CNN model architecture is predefined in the code. Feel free to modify the architecture based on your specific requirements.

The code assumes that the dataset folders contain PNG images. Modify the code accordingly if your dataset has a different image format.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Feel free to contribute, report issues, or suggest improvements!
