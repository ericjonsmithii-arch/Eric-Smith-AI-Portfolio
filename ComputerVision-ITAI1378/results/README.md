# Smart Inventory Counter Results

This folder contains the main outputs from the sHū addi Smart Inventory Counter proof of concept.

## Test Summary

- Hats: 3 actual, 0 detected
- Socks: 4 actual, 0 detected
- Backpacks: 2 actual, 2 detected
- Backpack labels were incorrect and appeared as suitcases
- Overall object-count recall: 22.2%

## Key Result

The system completed the full workflow of image upload, object detection, visual annotation, and automatic counting.

The main limitation was that the pretrained YOLO11 model did not contain the custom apparel classes needed for accurate recognition of hats, socks, and backpacks.

## Next Step

The next version would use a labeled sHū addi apparel dataset to fine-tune YOLO11 for the exact product categories needed by the business.
