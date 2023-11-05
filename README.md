# Object-Detection-Web-App-Using-YOLOv7-and-Flask
Object Detection Web App Using YOLOv7 and Flask

## Introduction

This project is an Object Detection Web Application that uses YOLOv7 for real-time object detection and Flask as the web framework. Follow the steps below to set up and use the application.

## Installation and Setup

1. Clone this GitHub repository:

https://github.com/shanmugamani1023/userinterface-of-YOLO.git


2. Import the provided `requirements.yaml` file using conda to set up the necessary environment:
Activate the conda environment:

3. Copy Your Custom Model:

Place your custom YOLOv7 model in the cloned repository. Make sure the model files are organized properly.

4. Configure Model Paths:

Open `webapp.py` and update the following lines to point to your custom model:

- Line 119: Change the path to the weights of your custom model.
- Line 124: Change the path to the configuration file of your custom model.

Ensure that the paths are accurate.

## Running the Application

To run the Object Detection Web App, execute the following command:

This will start the Flask application.

## Accessing the Web App

Open your web browser and navigate to [http://127.0.0.1:5000](http://127.0.0.1:5000).

You can now use the web application to upload images or videos for real-time object detection.

## Usage

1. Access the web app using the link mentioned above.

2. Upload an image or video that you want to analyze for object detection.

3. The application will process the input and display the results with bounding boxes and labels indicating detected objects.

## Conclusion

You have successfully set up and used the Object Detection Web App using YOLOv7 and Flask. Feel free to customize this application and extend its functionality as needed for your specific use case.


