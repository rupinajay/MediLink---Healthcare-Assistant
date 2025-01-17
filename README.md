# MediLink-Healthcare-Assistant

## Overview
Medilink is a comprehensive medical assistance and diagnosis system designed to provide various healthcare-related functionalities. Leveraging advanced technologies such as deep learning, OCR (Optical Character Recognition), real-time data analysis, and telemedicine integration, Medilink offers a wide range of services to users, including skin disease prediction, medical report analysis, heart rate simulation, prompt-based diagnosis, and telemedicine consultation.

## Features
### 1. Skin Disease Prediction System.  
- Predicts various skin diseases based on input images with high accuracy.
- Generates detailed diagnosis reports including predicted disease, confidence level, and description.
- Sends diagnosis reports to patients via email for further consultation.

### 2. OCR-based Medical Report Analyzer
- Allows users to upload medical report images.
- Extracts text from the uploaded images using OCR.
- Analyzes the medical report text to provide relevant information and insights.

### 3. Heart Rate Virtual Simulation and Real-time Data Analysis
- Simulates heart rate data in real-time.
- Provides insights into heart rate variations during resting and exercise conditions.
- Integrates with Firebase to store and manage heart rate data.

### 4. Prompt-based Diagnosis
- Allows users to input prompts related to medical queries.
- Utilizes language models to generate responses and insights based on user prompts.
- Displays the history of prompts and corresponding results for reference.

### 5. Telemedicine Integration
- Sends generated diagnosis reports via email to patients for remote consultation.
- Utilizes Gmail SMTP server for email communication.
- Ensures secure and efficient transmission of medical reports to patients.

## Dataset
- **NSL KDD Dataset**: The project utilizes the NSL-KDD dataset for training and evaluation. This dataset is a refined version of the widely-used KDD Cup 1999 dataset, specifically designed for intrusion detection research.

## Requirements
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- python-docx
- langchain_community library
- Streamlit (for OCR and prompt-based diagnosis)
- Firebase Admin SDK (for heart rate simulation and data management)

## Configuration
- Replace placeholder values (e.g., app passwords, API keys) with your actual credentials and keys.
- Ensure proper network configurations for real-time data analysis and telemedicine integration.

## Contributing
Contributions are welcome! Feel free to enhance existing features, add new functionalities, or fix any bugs. 

## License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Acknowledgments
- This project was developed as part of BOLT 2.0 VIT Hackathon 2024
- Special thanks to the creators of TensorFlow, Keras, Streamlit, Firebase, and other open-source libraries used in this project.

## Support
For any inquiries or issues, please contact rupinajay@gmail.com, sricharan320@gmail.com, sanjayperam2604@gmail.com, sukrithpvs2005@gmail.com
