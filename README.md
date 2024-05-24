# air-canvas-using-cv


Sure! Here is a README file description for your project:

Digital Workspace with Face Detection and Drawing Application
Overview
This project is a comprehensive digital workspace application that combines face recognition for authentication and a drawing application with a variety of tools. The application is built using Python and several libraries including OpenCV, Mediapipe, Tkinter, and SQLite3.

Features
Face Detection and Recognition:

Uses OpenCV and Mediapipe for detecting and recognizing faces.
Authenticates users based on pre-trained face recognition models.
Displays welcome messages upon successful login.
Drawing Application:

Provides a set of drawing tools including Line, Rectangle, Draw (freehand), Circle, and Eraser.
Features a color palette for selecting different drawing colors.
Allows saving the drawings to a file.
Option to clear the canvas or specific drawings.
User History:

Records user login history with timestamps in a SQLite database.
Displays user history in a separate window.
Provides an option to clear the user history.
User Interface:

Interactive and user-friendly interface using Tkinter.
Animated GIFs for visual appeal.
Requirements
Python 3.x
OpenCV
Mediapipe
Tkinter
PIL (Pillow)
SQLite3

Login Process:

The application will open with an animated welcome screen.
Click "Get Started" to begin the face detection process.
The camera will activate and attempt to recognize your face.
Upon successful recognition, you will be granted access to the drawing application.
Drawing Application:

Select tools from the toolbox by hovering your hand over the respective icon.
Use the selected tool to draw on the canvas.
Use the color palette to change the drawing color.
Save your drawing by clicking the save button.
Clear the canvas or specific drawings using the eraser tool.
View and Clear User History:

Click "HISTORY" on the main screen to view user login history.
Clear the history by clicking the "Clear" button.
Exit the Application:

Click "EXIT" on the main screen to close the application.
