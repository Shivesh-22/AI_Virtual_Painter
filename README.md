# AI_Virtual_Painter
    An AI-powered virtual painting tool that lets users paint and sketch using their hands and webcam. In order to intuitively select colours and write or erase on a digital canvas, this project makes use of OpenCV and unique hand-tracking features to identify hand positions and finger gestures.

Features

	•	Hand Gesture Recognition: Uses hand tracking to recognize specific gestures for mode selection and drawing.
	•	Virtual Painting: Allows users to draw on the canvas in real time using finger gestures.
	•	Color Selection: Switch between different colors by selecting options on the header area.
	•	Eraser Tool: Erase parts of the drawing using a virtual eraser gesture.

Requirements

	•	Python 3.x
	•	OpenCV (cv2)
	•	NumPy
	•	Custom Hand Tracking Module (Hand_Tracking_Module)

 Installation

    1.	Clone this repository:
         git clone https://github.com/yourusername/AI_Virtual_Painter.git
         cd AI_Virtual_Painter

    2.	Install required libraries:
         pip install numpy
         pip install mediapipe
         pip install cv2

    3. 	Set up the Hand Tracking Module: This project depends on a custom Hand_Tracking_Module that contains methods for detecting hands and fingers. Ensure this module is included in your project files.



Usage

	1.	Run the main script:
       python ai_virtual_painter.py
       
    2.	Interact with the application:
	    •	Use Index and Middle Finger Up: Selection Mode
	  •	Select colors or the eraser from the header (visible at the top of the screen).
	  •	Use Index Finger Up Only: Drawing Mode
	  •	Draw on the screen with the selected color or use the eraser for corrections.

	3.	Modes:
	  •	Colors and tools are selected based on hand position within certain areas at the top of the screen:
	  •	Magenta: Drawing color 1
	  •	Blue: Drawing color 2
  	•	Green: Drawing color 3
  	•	Black: Eraser


File Structure

	•	ai_virtual_painter.py: Main script for running the AI Virtual Painter.
	•	Header/: Directory containing images for the header icons representing different colors and tools.
	•	Hand_Tracking_Module.py: Custom module for hand tracking functionality (ensure this is in the project directory).


Acknowledgments

	•	OpenCV: For providing the tools for real-time computer vision.
	•	Mediapipe (Optional): If Mediapipe’s hand detection is used within Hand_Tracking_Module.

