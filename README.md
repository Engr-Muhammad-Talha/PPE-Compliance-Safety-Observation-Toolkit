# PPE Compliance & Safety Monitoring Toolkit
This repository contains an AI-powered platform designed to streamline the auditing and compliance monitoring of Personal Protective Equipment (PPE) across industrial and food sector environments. The toolkit leverages computer vision, deep learning, and interactive dashboards to assist safety personnel in identifying and documenting PPE violations in real time.

## Key Features:

- Real-Time PPE Detection: Utilizes a custom-trained YOLOv8 object detection model to identify PPE types including hairnets, goggles, masks, gloves, shoes, and full-body suits from images, videos, or live 
 webcam feeds.
    
- Interactive Web Interface: Built using Streamlit, the interface allows users to upload media files or use live streams for automated or manual analysis of PPE compliance.

- Visual Feedback: Detected objects are highlighted in-frame, aiding reviewers in quickly spotting non-compliant scenarios.

- Observation Reporting: The system auto-generates Safety Observation Cards that include checklists and behavioral evaluations based on detection results.

- Near Miss Analysis: Documents missing or improperly worn PPE and categorizes them as safety risks or near misses, enhancing proactive hazard prevention.

## Dataset & Model Training:
To build a robust and high-performing model, a dataset of approximately 6,000 images was annotated using Roboflow, a leading platform for image labeling, augmentation, and preprocessing. The curated dataset enabled precise model training, supporting reliable detection across various operational scenarios and lighting conditions.

## Visual Demonstration:

![Dashboard Picture](https://github.com/user-attachments/assets/37a75397-ac1c-4825-8c85-e77c96d3ca6d)
                        <p align="center"><em> Dasboard 1: (PPE Compliance Dashboard – Real-Time Monitoring Interface) </em></p>                                          
![Stop Card Table Generate ](https://github.com/user-attachments/assets/7d30098c-43c3-42d3-b5c6-26c4a5361fcf)
                        <p align="center"><em>  *Dashboard 2: (Automated Safety Observation Card for PPEs Evaluation </em></p>
![Punitive Atmosphere Card](https://github.com/user-attachments/assets/47f5b796-1961-4373-85aa-bfe28ebeb88b)
                        <p align="center"><em>( *Dashboard 3: (Observation Description Auto-Generated Based on Detected Violations* </em></p>

## Project Overview:

This toolkit utilizes advanced computer vision and deep learning techniques to automate the detection of Personal Protective Equipment (PPE) usage in industrial and food processing environments. Designed to enhance workplace safety and ensure regulatory compliance, the system identifies whether essential PPE—such as masks, gloves, goggles, and full-body suits—is correctly worn by personnel in real-time across images, videos, and live feeds.

## Files Included:

- **PPECodeFile.py**: Core application script responsible for executing the PPE compliance monitoring logic and interfacing with the user interface.
- **requirements.txt**: Contains a list of required Python packages and libraries necessary to run the application environment.
- **best.pt**: Pre-trained YOLOv8 model (PyTorch format) specifically optimized for PPE detection across various workplace scenarios.
- **stop logo.png**: Visual identifier (logo) used for branding within the application's interface.

## How to use
1. Clone the repository:
    ```bash
    git clone https://github.com/Engr-Talha-Amjad/PPE Compliance & Safety Monitoring Toolkit.git
    ```
2. Install Dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Prepare the YOLOv8 Model:
- Obtain a trained YOLOv8 model for PPE detection (e.g., best.pt). You can train your own model or download a pre-trained one.
- Place the model file in the project root directory or update the path in PPECodeFile.py (line: model = YOLO("path/to/best.pt")).
  
4. Run the Application:
      ```bash
      streamlit run PPECodeFile.py
      ```

5. Usage Instructions:

- **Select Source:** Choose "Image," "Video," or "Webcam" from the sidebar.
- **Select Process**: Choose "Automatic" for YOLOv8-based detection or "Manual" for custom input.
- **Select Sections**: Pick PPE sections (e.g., Head, Eyes, All) to analyze.
- **Upload** An image/video, select a frame, or start the webcam, then click "Detect Objects" to analyze PPE compliance.
- **Generate a Safety Observation Card PDF** By filling in the required fields and clicking "Generate Safety Report."

## License
   This project is licensed under the MIT License - see the LICENSE file for details.

## Contact
   For any questions or issues, feel free to reach out at **talhaamjad730@gmail.com**.


	




