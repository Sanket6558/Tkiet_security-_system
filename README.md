# Tkiet_security-_system
Tatasaheb Kore Institute of Engineerng and Technology
Here's a README file template for your project:

---

# AI Camera: Tracking Suspicious Activity

## Description
This project involves the implementation of an AI-powered camera system capable of detecting and tracking suspicious activities, particularly focusing on identifying potential threats such as fire or weapons. It utilizes deep learning techniques for object detection and classification, and integrates various technologies such as computer vision, machine learning, and communication APIs.

## Features
- Real-time object detection and classification using a trained deep learning model.
- Integration with Twilio API for sending SMS notifications when suspicious activity is detected.
- Auditory alert system using pygame for immediate attention to potential threats.
- Graphical user interface (GUI) built with Tkinter for user interaction and control.
- Video recording functionality to capture footage of detected incidents.
- Framerate monitoring for performance evaluation and optimization.

## Prerequisites
- Python 3.x installed on your system.
- Required Python libraries:
  - boto3
  - keras
  - opencv-python
  - numpy
  - pygame
  - twilio
  - tkinter
  - pillow

## Installation
1. Clone this repository to your local machine:
   ```
   git clone https://github.com/your_username/AI-Camera.git
   ```
2. Navigate to the project directory:
   ```
   cd AI-Camera
   ```
3. Install the required Python libraries:
   ```
   pip install -r requirements.txt
   ```
4. Download the pre-trained model weights (`keras_Model.h5`) and label file (`labels.txt`) to the project directory.

## Usage
1. Run the `main.py` script to start the application:
   ```
   python main.py
   ```
2. Upon execution, a login window will appear. Enter the username and password to access the security system.
3. Once logged in, the main application window will open, displaying the live webcam feed.
4. Click the "Detect Objects" button to initiate the object detection process.
5. If any suspicious activity (e.g., fire, weapon) is detected, you will hear an auditory alert, and an SMS notification will be sent to the specified phone number.
6. To quit the application, click the "Quit" button or close the window.

## Contributors
- Prathamesh Dilip Chogule (Group Leader)
- Tejas Kiran Patil
- Pranav Abhijit Gatade
- Sanket Kishorkumar Deshmukh

## License
This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this README file according to your project's specific details and requirements. If you have any further questions or need assistance, don't hesitate to ask!
