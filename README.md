# YOLOv8 Object Detection on MOT17 Dataset in Google Colab

This notebook demonstrates how to perform object detection using YOLOv8 on the MOT17 dataset, with annotations done using Roboflow.

## Requirements

- Google Colab
- Roboflow account for dataset annotation

## Setup Instructions

1. **Open this notebook in Google Colab**.
2. **Run the first cell** to install the required libraries.
3. **Upload the MOT17 dataset** to your Google Drive and unzip it in the specified directory.
4. **Annotate your dataset using Roboflow**:
   - Create a new project and upload your images.
   - Annotate the images and export the dataset in YOLO format.
   - Upload the exported dataset to your Google Drive.
5. **Run the remaining cells** to train the model and perform object detection.

## Usage

- The model will train for 50 epochs.
- It will process videos in the MOT17 dataset and display the annotated frames.

## License

This project is licensed under the MIT License.
