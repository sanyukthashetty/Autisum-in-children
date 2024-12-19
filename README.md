# Machine Learning-Based Early Detection of Autism in Children

This project utilizes machine learning, specifically Convolutional Neural Networks (CNN), for the early detection of Autism Spectrum Disorder (ASD) in children. By analyzing image data, the system provides healthcare professionals with accurate and efficient diagnostic assistance, promoting timely interventions and improved outcomes for children at risk of ASD.

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [System Workflow](#system-workflow)  
4. [Setup and Installation](#setup-and-installation)  
5. [Usage](#usage)  
6. [Dataset and Preprocessing](#dataset-and-preprocessing)  
7. [Technologies Used](#technologies-used)  
8. [Results](#results)  
9. [Future Enhancements](#future-enhancements)  
10. [Contributors and Roles](#contributors-and-roles)  

---

## Project Overview
The goal of this project is to develop a reliable and efficient machine learning-based system to detect Autism Spectrum Disorder (ASD) using image analysis. The system leverages advanced CNN architectures, transfer learning, and a user-friendly Flask interface to deliver high accuracy and usability.

---

## Features
- **Data Preprocessing**: Steps such as image alignment, cropping, normalization, and augmentation enhance data quality.  
- **CNN Model**: A convolutional neural network trained on preprocessed data ensures robust classification.  
- **Flask Web Interface**: Provides an accessible platform for users to upload images and view results.  
- **Accuracy Validation**: Reliable model validation ensures accurate predictions.  

---

## System Workflow
1. Input images are preprocessed to enhance quality and ensure uniformity.  
2. Preprocessed data is fed into the CNN for training and classification.  
3. The system evaluates the test accuracy and optimizes the model as needed.  
4. Results are displayed via the Flask-based user interface.  

---

## Setup and Installation

### Prerequisites
- Python 3.8 or later  
- Required Python libraries (detailed in `requirements.txt`)  

### Installation Steps
1. Clone the repository:  
   ```bash
   git clone https://github.com/username/asd-early-detection.git
   ```  
2. Navigate to the project folder:  
   ```bash
   cd asd-early-detection
   ```  
3. Install the dependencies:  
   ```bash
   pip install -r requirements.txt
   ```  
4. Run the Flask application:  
   ```bash
   python app.py
   ```  

---

## Usage
1. Launch the Flask web application in your browser.  
2. Upload an image of a child for ASD detection.  
3. View the classification results, including the prediction and model accuracy.  

---

## Dataset and Preprocessing

### Dataset
Contains images reflecting features associated with ASD.

### Preprocessing Steps
- **Alignment and Cropping**: Ensures consistent dimensions across the dataset.  
- **Normalization**: Standardizes pixel values for uniform input.  
- **Augmentation**: Increases data diversity to improve model robustness.  

---

## Technologies Used
- **Programming Language**: Python  
- **Frameworks and Libraries**: TensorFlow, Keras, Flask, OpenCV  
- **Tools**: Jupyter Notebook, Anaconda Navigator  

---

## Results
- High classification accuracy achieved through effective model training and validation.  
- Demonstrated reliability and robustness in real-world testing scenarios.  

---

## Future Enhancements
- Integrate multimodal data such as behavioral patterns and demographic information.  
- Explore advanced architectures (e.g., transformers) for enhanced accuracy.  
- Deploy as a cloud-based service for better accessibility and scalability.  

---

## Contributors and Roles

### Sarina
- **Role**: Lead Developer & Project Manager  
- **Responsibilities**:  
  - Designed and developed the CNN-based model.  
  - Managed project milestones and overall system integration.  

### Sanyuktha Shetty
- **Role**: Dataset Curator & Preprocessing Specialist  
- **Responsibilities**:  
  - Curated and prepared the dataset for training and testing.  
  - Implemented data preprocessing techniques such as augmentation and normalization.  

### Sammrudhi H R
- **Role**: Model Trainer & Optimizer  
- **Responsibilities**:  
  - Trained the CNN model and implemented transfer learning.  
  - Optimized the model for improved test accuracy.  

### Shraddha Singh
- **Role**: Flask Integration & UI Developer  
- **Responsibilities**:  
  - Designed and developed the Flask web interface.  
  - Integrated the model with the user interface for seamless user interaction.  

### Miliyana Reena Dsouza
- **Role**: Testing & Validation Engineer  
- **Responsibilities**:  
  - Performed rigorous testing to validate model accuracy and reliability.  
  - Ensured the system meets performance benchmarks.  


