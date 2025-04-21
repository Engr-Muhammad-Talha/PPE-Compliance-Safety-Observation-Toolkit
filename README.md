# PPE Compliance & Safety Monitoring Toolkit

This repository contains an AI-powered platform designed to streamline the auditing and compliance monitoring of Personal Protective Equipment (PPE) across industrial and food sector environments. The toolkit leverages computer vision, deep learning, and interactive dashboards to assist safety personnel in identifying and documenting PPE violations in real time.

## 🔍 Key Features

- Real-Time PPE Detection: Utilizes a custom-trained YOLOv8 object detection model to identify PPE types including hairnets, goggles, masks, gloves, shoes, and full-body suits from images, videos, or live 
 webcam feeds.
    
- Interactive Web Interface: Built using Streamlit, the interface allows users to upload media files or use live streams for automated or manual analysis of PPE compliance.

- Visual Feedback: Detected objects are highlighted in-frame, aiding reviewers in quickly spotting non-compliant scenarios.

- Observation Reporting: The system auto-generates Safety Observation Cards that include checklists and behavioral evaluations based on detection results.

- Near Miss Analysis: Documents missing or improperly worn PPE and categorizes them as safety risks or near misses, enhancing proactive hazard prevention.

## Dataset & Model Training
To build a robust and high-performing model, a dataset of approximately 6,000 images was annotated using Roboflow, a leading platform for image labeling, augmentation, and preprocessing. The curated dataset enabled precise model training, supporting reliable detection across various operational scenarios and lighting conditions.

## Visual Demonstration:

![Dashboard Picture](https://github.com/user-attachments/assets/37a75397-ac1c-4825-8c85-e77c96d3ca6d)
                         <p align="center"><em> Dasboard 1: (PPE Compliance Dashboard – Real-Time Monitoring Interface) </em></p>
                                                                                
![Stop Card Table Generate ](https://github.com/user-attachments/assets/7d30098c-43c3-42d3-b5c6-26c4a5361fcf)
                        <p align="center"><em>  *Dashboard 2: (Automated Safety Observation Card for PPEs Evaluation </em></p>
![Punitive Atmosphere Card](https://github.com/user-attachments/assets/47f5b796-1961-4373-85aa-bfe28ebeb88b)
                        <p align="center"><em>( *Dashboard 3: (Observation Description Auto-Generated Based on Detected Violations* </em></p>





	




