# OCR Preprocessing and Recognition Project

## Project Overview
This Python project utilizes the Tesseract OCR engine through the pytesseract wrapper and the Python Imaging Library (PIL) to perform Optical Character Recognition (OCR) on images. The main goal is to compare the accuracy of OCR results with and without various image preprocessing methods.

## Features
- **Tesseract OCR Integration**: Utilize the Tesseract engine to extract text from images.
- **Image Preprocessing**: Implement different image preprocessing techniques like erosion, dilation, and color filtering to enhance OCR accuracy.
- **Accuracy Measurement**: Calculate the OCR accuracy using the Levenshtein distance, providing a metric for comparing different preprocessing methods.

## Prerequisites
- Python 3.x
- pytesseract
- Pillow (PIL)
- OpenCV
- NumPy

## Installation

1. **Install Python Packages**:

2. **Tesseract OCR**:
- Download and install Tesseract from [Tesseract GitHub](https://github.com/tesseract-ocr/tesseract).
- Ensure the Tesseract path is configured correctly in the script:
  ```python
  pytesseract.pytesseract.tesseract_cmd = r"C:\\Program Files\\Tesseract-OCR\\tesseract.exe"
  ```

## Usage

1. **Load the Image**:
- Place the image you want to process in the project directory.

2. **Run the Script**:
- Execute the Python script to perform OCR on the image.
- Adjust the preprocessing functions as needed to compare different results.

3. **View Results**:
- The script will display the original and preprocessed images along with their OCR results and accuracy.

## Contributing
Contributions to enhance the functionality or the efficiency of the OCR process are welcome. Please ensure to submit a pull request with a clear description of your changes.


