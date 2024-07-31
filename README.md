OCR Reading Application
This project is an OCR (Optical Character Recognition) reading application built with Python. The app extracts text from images using Tesseract OCR and provides a simple interface for users to upload images and view the extracted text.

Features
Extracts text from images using Tesseract OCR.
Provides a web-based interface for uploading images.
Displays extracted text in a user-friendly format.
Requirements
Python 3.x
Flask
pytesseract
Pillow
Tesseract-OCR
Setup Instructions
Clone the Repository



On Windows: Download and install Tesseract from this link and add it to your system PATH.
On macOS: Install using Homebrew:
bash
Copy code
brew install tesseract
On Linux: Install using apt:
bash
Copy code
sudo apt-get install tesseract-ocr
Run the Flask Application





Upload an image file containing text.
The app will process the image using Tesseract OCR and display the extracted text.
Troubleshooting
404 Error: Ensure that you have correctly started the Flask server and that you're accessing the correct URL.
Tesseract Not Found: Verify that Tesseract is correctly installed and added to your system PATH. You can check the installation by running tesseract --version in your terminal.
OCR Errors: Ensure that the image quality is good and contains clear text. Tesseract performs best with high-resolution images and clear fonts.
