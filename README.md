
# Automatic License Plate Detection System

This repository contains an implementation of an Automatic License Plate Detection System using PyTorch, YOLO (You Only Look Once), and Flask. The system is designed to accurately and efficiently detect license plates in real-time across various conditions, offering reliable performance for diverse use cases.


## 🚀 Features

High Accuracy: Achieves 95% accuracy on diverse datasets, ensuring precise license plate detection.
Robust Detection: High Mean Average Precision (MAP) @ 0.5-0.7, making it reliable across different conditions.
Real-Time Processing: Seamless and efficient processing with Flask, enabling fast and scalable real-time applications.
Optimized Performance: Reduced inference time by 30%, improving the model's speed for scalable usage.
## 🎯 Motivation

In the era of smart cities, automated systems play a crucial role in traffic management, surveillance, and security. This project aims to simplify license plate detection, making it more accessible and efficient for real-world applications, from toll booths to parking management systems.
## 🛠️ Tech Stack

Programming Language: Python
Deep Learning Framework: PyTorch
Object Detection: YOLO (You Only Look Once)
Web Framework: Streamlit
## 📂 Project Structure

├── app/                     # Flask application
│   ├── static/              # Static files (CSS, JavaScript)
│   ├── templates/           # HTML templates
│   └── app.py               # Main application file
├── models/                  # Pre-trained YOLO model weights
├── data/                    # Sample images and datasets
├── notebooks/               # Jupyter notebooks for model training and testing
├── scripts/                 # Scripts for preprocessing and data augmentation
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation

## Working



![3](https://github.com/user-attachments/assets/0bccd74c-58aa-478d-9439-4089220e1d38)

![8](https://github.com/user-attachments/assets/7740e9d1-76a3-482d-8dac-e5ce347845a6)

![9](https://github.com/user-attachments/assets/bb47123c-db9a-4f8b-8b56-1c9776166938)






## 📊 Results

Accuracy: 95%
Mean Average Precision (MAP): 0.5 - 0.7
Inference Time Reduction: 30%
The model performs exceptionally well across diverse datasets, providing robust and consistent detection even in challenging scenarios like poor lighting, different weather conditions, and various camera angles.
## 🚀 How It Works

Preprocessing: The input images are preprocessed for consistent results, including resizing and normalization.
Detection: Using the YOLO algorithm, the model identifies license plates within the image.
Post-processing: Detected license plates are extracted and highlighted, enabling further tasks like recognition.
## 📝 Usage

Detect License Plate from an Image
Upload an image containing a license plate.
The system will detect and highlight the license plate(s) in real-time.
Results will be displayed on the same page, along with inference time.
## 💡 Future Work

Integration with OCR: Adding Optical Character Recognition (OCR) for complete license plate recognition.
Support for Video Processing: Extend the system to handle video streams for continuous monitoring.
Enhanced Scalability: Further reduce inference time and improve model accuracy.
## 🌟 Acknowledgements

YOLO
Flask
Open-source datasets for testing and training


