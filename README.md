# License-Plate-Recognition
## License Plate Detection using OpenCV and EasyOCR

This project demonstrates license plate detection using OpenCV and EasyOCR. The goal is to detect license plates in an image, extract the text from the detected plate, and display the result.


## Getting Started
### Prerequisites
To run the code and experiments, you'll need the following:

  - Python     
  - Jupyter Notebook 
  -  OpenCV  
  -  matplotlib
  -  numpy
  -  imutils
  -  easyocr

You can install the required libraries using the following command:   
 ```bash
pip install opencv-python matplotlib numpy imutils easyocr

```
## Installation
To get started, follow these steps:   
  1. Clone the repository to your local machine:
```bash
git clone https://github.com/shreyas-rp/License-Plate-Recognition-.git
```
  2. Navigate to the project directory:
```bash
cd License-Plate-Recognition-
```
  3. Run the Jupyter Notebook file:
```bash
jupyter notebook DeepLearning_MNIST_Classification.ipynb
```
## Procedure 
1. **Dataset Loading**: The MNIST dataset is loaded using Keras, consisting of 60,000 training images and 10,000 test images, each of size 28x28 pixels.  
2. **Data Preprocessing**: Images are reshaped and scaled, and labels are one-hot encoded.  
3. **Model Architecture**: A neural network model with two layers is created using Keras.   
4. **Model Compilation**: The model is compiled using the rmsprop optimizer and categorical crossentropy loss.   
5. **Model Training**: The model is trained for 10 epochs with a batch size of 128.   
6. **Model Evaluation**: After training, the model's performance is evaluated on the test dataset and the predictions and actual labels are also shown.

# Results
  - Upon running the Jupyter Notebook, you'll see the training progress and final evaluation results, including accuracy and the actual and predicted labels for the digits.
    
  - Feel free to experiment with different hyperparameters and model architectures to improve accuracy.
