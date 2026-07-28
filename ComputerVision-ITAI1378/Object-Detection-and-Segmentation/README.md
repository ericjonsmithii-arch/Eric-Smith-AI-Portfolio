# Object Detection and Image Segmentation

## Problem Statement

This lab explored the difference between object detection and image segmentation. The goal was to identify objects with bounding boxes, create pixel-level masks, and compare a specialist model with a foundation segmentation model.

## Approach

The project used YOLO11 for object detection, YOLO11-seg for instance segmentation, and SAM 2 for prompted segmentation. The models were tested in Google Colab using sample images and a second test image.

## Results

YOLO11 successfully detected common objects and displayed class labels, confidence scores, and bounding boxes. YOLO11-seg produced masks for individual objects. SAM 2 used YOLO11 bounding boxes as prompts to create more detailed segmentation masks.

## Key Findings

- Detection identifies object locations with bounding boxes.
- Segmentation identifies the exact pixels belonging to each object.
- Confidence thresholds change the number and reliability of detections.
- YOLO11 provides labels and masks for known classes.
- SAM 2 creates masks from prompts but does not provide class labels.
- Specialist and foundation models can be combined in one workflow.

## Technologies Used

- Python
- Google Colab
- Ultralytics YOLO11
- YOLO11-seg
- SAM 2
- Matplotlib
- Pillow
- NumPy

## How to Run

1. Open the notebook in Google Colab.
2. Run each cell from top to bottom.
3. Allow the model weights to download.
4. Review the detection boxes, segmentation masks, and written outputs.
