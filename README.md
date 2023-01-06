# Text-Extractor
In this python project, I have made a text extractor from an image using  OCR. I've used Tesseract engine to perform the character recognition system and the  pytesseract python package to interact with Tesseract in python.

1 About Text Detection & Extraction Project
In this python project, we‟re going to make a text detector and extractor from an image using 
ocr. We‟ll use the Tesseract engine to perform the character recognition system and the 
pytesseract python package to interact with Tesseract in python.
1.2 Components of Project
1.2.1 OCR
OCR or Optical Character Recognition is a system that can detect characters or text from a 
2d image. The image could contain machine-printed or handwritten text. OCR can detect 
several languages, for example, English, Hindi, German, etc.
OCR is a widely used technology. Some popular real-world examples are:
 Automatic number plate recognition.
 At airports, passport recognition and information extraction.
 Converting handwriting in real-time to control a computer (pen computing).
1.2.2 Tesseract
Tesseract is an optical image recognition engine that runs on various operating systems. It can 
detect more than 100 languages from all over the world. Tesseract is originally written in 
C/C++. But we are going to use it in python.
1.2.3 Pytesseract
Python-tesseract is a wrapper for Tesseract-OCR Engine. It allows us to interact with the 
tesseract engine using python.
1.2.4 Challenges with Tesseract
 Tesseract doesn‟t perform well if the image contains a lot of noise.
 If the font of any language is not trained then tesseract cannot detect that language 
accurately.
 Image brightness or skewness may affect Tesseract‟s performance as well.
1.3 Project Prerequisites:
 Python – 3.x (we used Python 3.9. in this project)
 Tesseract Engine – v5.0.0 
Please download the Tesseract engine executable (.exe) file and install it in 
“C:\Program Files\Tesseract-OCR\tesseract.exe” directory
 Pytesseract – v0.3.7
Please run below command to install the latest version of Pytesseract:
pip install pytesseract
