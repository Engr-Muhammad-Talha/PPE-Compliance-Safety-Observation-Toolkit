# PPE-Compliance-Safety-Observation-Toolkit
This repository presents a deep learning-based toolkit designed to monitor Personal Protective Equipment (PPE) compliance through computer vision. It is developed to assist safety officers, supervisors, and compliance managers in automatically identifying whether individuals are wearing the required PPE — including masks, gloves, hairnets, goggles, and full-body suits — across images, videos, or real-time streams from industrial and food processing environments.
# Core Functionality
The system is powered by a custom-trained YOLO (You Only Look Once) object detection model, enabling accurate and real-time identification of PPE usage. The detection module is integrated into a Streamlit-based web interface, allowing users to:

•	Upload images or video footage
•	Monitor live streams from workplace environments
•	Analyze content frame-by-frame to detect PPE violations

This ensures a streamlined and automated approach to safety oversight, minimizing the need for manual monitoring.
# Dataset & Model Training
To build a robust and high-performing model, a dataset of approximately 6,000 images was annotated using Roboflow, a leading platform for image labeling, augmentation, and preprocessing. The curated dataset enabled precise model training, supporting reliable detection across various operational scenarios and lighting conditions.
