# Image Segmentation with YOLOv8

This repository demonstrates the use of [YOLOv8](https://github.com/ultralytics/ultralytics), a state-of-the-art deep learning model, for image segmentation and object detection. The project includes a web application that allows users to upload an image and view the identified segments, providing a practical understanding of YOLOv8's capabilities in image segmentation.

## Features

- **Image Segmentation**: Utilizes YOLOv8 to segment images into distinct regions.
- **Object Detection**: Identifies and classifies objects within an image.
- **Web Application**: Interactive interface for uploading images and visualizing segmentation results.

## Requirements

Ensure you have the following dependencies installed:

- Python 3.8 or higher
- PyTorch
- OpenCV
- Streamlit
- Ultralytics YOLOv8

Install the required packages using:

```bash
pip install -r requirements.txt
```

## Usage

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/aleale2121/Image-Segmentation-YOLOv8.git
   cd Image-Segmentation-YOLOv8
   ```

2. **Download YOLOv8 Model Weights**:

   Ensure you have the YOLOv8 model weights file (`yolov8n.pt`) in the repository directory. You can download it from the [Ultralytics YOLOv8 repository](https://github.com/ultralytics/ultralytics).

3. **Run the Web Application**:

   The web application is built using Streamlit. To start the app, execute:

   ```bash
   streamlit run segmentation.py
   ```

   This will launch the application in your default web browser.

4. **Upload and Segment Images**:

   You can upload an image using the web interface. The application will process the image using YOLOv8 and display the segmented output.


*Note: Ensure the `yolov8n.pt` file is in the repository directory before running the application. If it's not included due to file size constraints, download it from the official Ultralytics repository.*
