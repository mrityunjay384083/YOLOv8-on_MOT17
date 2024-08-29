# YOLOv8 Object Detection on MOT17 Dataset in Google Colab

This notebook demonstrates how to perform object detection using YOLOv8 on the MOT17 dataset, with annotations done using Roboflow.

## Requirements

- Google Colab
- Roboflow account for dataset annotation
**The steps to train a YOLOv8 object detection model on custom data are:**
1. Install YOLOv8 from pip
2. Create a custom dataset with labelled images
3. Export your dataset for use with YOLOv8
4. Use the yolo command line utility to run train a model
5. Run inference with the YOLO command line application
## Setup Instructions

1. **Open this notebook in Google Colab**.
2. **Run the first cell** to install the required libraries.
3. **Upload the MOT17 dataset** to your Google Drive and unzip it in the specified directory.
4. **Annotate your dataset using Roboflow**:
   - Create a new project and upload your images.
   - Annotate the images and export the dataset in YOLO format.
   - After annotation and required pre-processing an API will generate automatically. The generated API will redirect to the google colab environment.
5. **Run the remaining cells** to train the model and perform object detection.

## Usage

- The model will train for 50 epochs.
- It will process videos in the MOT17 dataset and display the annotated frames.

## License

This project is licensed under the MIT License.
