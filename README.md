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
jupyter notebook licence plate.ipynb

```
## Procedure 
1. **Image Loading:** The script loads the input image ('image4.jpg') using OpenCV.  
2. **Preprocessing:** The image is converted to grayscale to reduce complexity and facilitate edge detection. 
3. **Edge Detection:** The Canny edge detection algorithm is applied to identify potential edges in the image.  
4. **Contour Extraction:** Contours are identified in the edge-detected image using the findContours function from OpenCV.   
5. **License Plate Location:** The script identifies the location of the license plate by approximating a quadrilateral contour that matches the shape of the plate   
6. **Cropping:** The detected license plate region is cropped from the original image.
7. **Text Recognition:** The cropped image containing the license plate text is passed to the EasyOCR reader, which extracts the text.
8. **Text Overlay:** The extracted text is displayed on the original image along with a rectangle drawn around the detected license plate. 
# Results
  - Upon running the script, you will see the original image with the detected license plate, and the extracted text will be displayed on the image. The text represents the characters recognized from the license plate.
    
  - Feel free to experiment with different images or try fine-tuning the parameters for better license plate detection results.
