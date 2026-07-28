# sHū addi Smart Inventory Counter

## Problem Statement

Small apparel businesses often count inventory manually. This process can take time, lead to missed items, and make restocking decisions less reliable.

The goal of this project was to test whether computer vision could automatically detect and count visible products from uploaded retail images.

## Approach

The project used a pretrained YOLO11 Nano object-detection model in Google Colab.

The notebook:

1. Uploads a product image
2. Processes the image with YOLO11
3. Draws bounding boxes around detected objects
4. Displays predicted class labels and confidence scores
5. Counts the detected object classes
6. Produces a written inventory summary

## Results

Three product tests were completed:

- Hats: 3 actual, 0 detected
- Socks: 4 actual, 0 detected
- Backpacks: 2 actual, 2 detected
- Both backpacks were incorrectly labeled as suitcases
- Overall object-count recall: 22.2%

## Key Findings

- The complete image-upload, detection, annotation, and counting workflow worked.
- The pretrained model could not recognize the custom hat and sock categories.
- Correct object counts did not guarantee correct class labels.
- A specialized apparel model would require a labeled custom dataset.
- Honest failure analysis provided a useful baseline for future development.

## Technologies Used

- Python
- Google Colab
- Ultralytics YOLO11
- Matplotlib
- Pillow
- GitHub

## Project Repository

[View the complete sHū addi Smart Inventory Counter repository](https://github.com/ericjonsmithii-arch/SHU-Addi-Smart-Inventory-Counter)

## Demo Video

[Watch the project demonstration](https://drive.google.com/file/d/1Cm47Ld-pSXY3knSoAZqMbzkW2t-9XzhT/view?usp=share_link)

## How to Run

1. Open the notebook in Google Colab.
2. Run each cell from top to bottom.
3. Upload product images when prompted.
4. Review the annotated detections and inventory counts.
