# Hairstyle AI Project

This repository contains a project for face shape and skin tone based hairstyle recommendation and natural hairstyle transfer using AI.

## Directory Structure

```
hairstyle_ai_project/
│
├── backend/
│   ├── model_training/
│   │   ├── face_shape_classifier.py
│   │   ├── skin_tone_detector.py (to be implemented)
│   │   └── hairstyle_recommendation.py (to be implemented)
│   └── image_generation/
│       ├── hairstyle_transfer_gan.py (to be implemented)
│       └── inference.py (to be implemented)
│
├── data/
│   ├── faces/ (image dataset)
│   └── labels/ (face shape and skin tone labels)
│
├── frontend/
│   ├── app_ui/
│   │   └── streamlit_app.py (to be implemented)
│
├── requirements.txt
├── README.md
└── .gitignore
```

## Initial Setup

1. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install required packages:
   ```bash
   pip install mediapipe opencv-python numpy
   ```

3. Run face shape classifier:
   ```bash
   python backend/model_training/face_shape_classifier.py path_to_face_image.jpg
   ```

