Hand Sign Recognition System

**Overview**

The Hand Sign Recognition System is a real-time application that uses computer vision and deep learning to recognize hand signs. This project leverages the power of Convolutional Neural Networks (CNN) to interpret hand gestures and convert them into corresponding alphabets and words. The application is built using Python, OpenCV, TensorFlow/Keras, and Tkinter for the GUI.

**Features**

Real-time hand sign detection and recognition using webcam.
Support for the English alphabet (A-Z) and blank gestures.
Interactive GUI with suggestions for word completions.
Prerequisites
Python 3.x
OpenCV
NumPy
Tkinter
PIL (Pillow)
Enchant
TensorFlow/Keras


**Installation**

Clone the repository:
git clone https://github.com/piyu-priyanshu/hand-sign-recognition.git
cd hand-sign-recognition

Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

Install the required dependencies:
pip install -r requirements.txt

Download and place the model files:
Place the model JSON and H5 files in the Models/ directory.

**Usage**

Run the application:
python hand_sign_recognition.py

Using the GUI:
The main window displays the real-time feed from your webcam.
Detected hand sign and the recognized character, word, and sentence will be displayed.
Use the suggestion buttons to complete words based on recognized characters.

**Acknowledgements**

TensorFlow/Keras for the deep learning models.
OpenCV for image processing.
Tkinter for the GUI.
Enchant for word suggestion functionality.
