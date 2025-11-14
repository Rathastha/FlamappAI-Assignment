# Flamapp.AI Assignment – My Submission

This repository contains my work for the Flamapp.AI Android + OpenCV + C++ + OpenGL + Web assignment. I followed the instructions given in the PDF and tried to complete the required features with the knowledge I currently have.



#Features Implemented

#Android App
- Basic camera preview using TextureView / Camera2.
- Sent camera frames from Java/Kotlin to the native C++ layer using JNI.
- Applied simple image processing using OpenCV in C++ (like grayscale or Canny edges).
- Sent the processed frame back to Android.
- Displayed the result using an OpenGL ES texture.
- Added a toggle button to switch between original and processed output.

#Native (C++ / OpenCV)
- Loaded the camera frame into an OpenCV Mat.
- Ran simple processing (grayscale / edge detection).
- Returned the processed buffer to the Java side.

#Web Viewer (TypeScript)
- A very small webpage that shows a sample processed image.
- Added basic UI text for FPS/resolution (dummy values).
- Simple TypeScript setup with clean code.


