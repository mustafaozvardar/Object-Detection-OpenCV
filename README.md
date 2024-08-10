# 🎯 **Real-Time Object Detection with OpenCV**

This project implements a real-time object detection system using OpenCV and a pre-trained SSD MobileNet model. The application captures video from your webcam and detects objects in the video feed, labeling them with their corresponding names and confidence scores.

## **🛠️ Requirements**

To run this project, you'll need to install the following libraries:

- **OpenCV** `opencv-python`

You can install the library using **pip**. 

**opencv-python==4.6.0.66**

**Then, you need to download these files and upload them into your project:**

**--> Link: <a href="https://usercontent.one/wp/www.computervision.zone/wp-content/uploads/2020/08/Object_Detection_Files.zip?media=1632743877">Object_Detection_Files</a>**

## **Model and Config Files**

**Model Weights:** frozen_inference_graph.pb - The pre-trained model weights file.

**Model Config:** ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt - The configuration file for the SSD MobileNet model.

## **COCO Names**

**coco.names:** Contains the names of the 80 object categories used by the COCO dataset. These are the classes that the model can detect.

## **🎮 How to Use**

**Prepare Files:** Ensure the model files (frozen_inference_graph.pb, ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt) and coco.names are located in the same directory as your script.

**Run the Script:** Start the script using Python. Make sure your webcam is active.

**--> python main.py**

**Object Detection:** The script will display the video feed with bounding boxes around detected objects, along with labels showing the object names and confidence scores.

**Exit:** Press the q key to close the video feed window and stop the script.

## **📄 License**

This project is licensed under the MIT License. Feel free to use, modify, and distribute this project as you wish.
