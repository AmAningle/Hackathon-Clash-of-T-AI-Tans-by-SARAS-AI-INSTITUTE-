



# Diet Analysis Project

## Overview

The Diet Analysis Project aims to analyze meal images for nutritional content and generate recommendations based on the user's dietary information. The project utilizes YOLO for object detection, Google Generative AI for content generation, and Gradio for user interface deployment.

## Dataset Description

This project does not rely on a specific dataset for training, as it uses YOLO for object detection of food items and Google Generative AI for nutrition analysis based on the detected food items.


## Requirements

- Python packages: `gradio`, `ultralytics`, `google-generativeai`, `pillow`, `numpy`, `opencv-python`
- YOLO model weights file
- Google Generative AI API key

## Execution Instructions

1. **Install Dependencies**:
   ```bash
   pip install gradio ultralytics google-generativeai pillow
   ```

2. **Set Environment Variables**:
   - `GEMINI_API_KEY`: Your Google Generative AI API key.
   - `YOLO_MODEL_PATH`: Path to the YOLO model weights file.

## Results

The project outputs include:

- **Nutrition Information**: Quantities of detected food items.
- **Macronutrient Breakdown**: Estimated calories, protein, carbohydrates, and fat.
- **RDA Table**: Recommended daily allowances and dietary suggestions.
