Machine Learning-Based Early Detection of Autism in Children
This project leverages machine learning, specifically Convolutional Neural Networks (CNN), to detect Autism Spectrum Disorder (ASD) in children. It aims to support early diagnosis by analyzing image data and providing healthcare professionals with efficient and accurate predictions. The system is built with a user-friendly Flask interface for seamless interaction.
Features
•	Detects Autism Spectrum Disorder through a pre-trained CNN model.
•	Simple and interactive user interface built with Flask.
•	Handles image preprocessing, including alignment, cropping, and normalization.
•	Provides model accuracy metrics for user evaluation.
•	Customizable for integration with other healthcare systems.
Installation
Follow the steps below to set up and run the project locally:
Prerequisites
1.	Python 3.8 or higher installed on your system.
2.	Required Python libraries (listed in requirements.txt).
Steps to Run
1.	Download the repository
Download the project files and navigate to the project folder.
2.	Install dependencies
Install the required libraries using pip:
3.	pip install -r requirements.txt
4.	Set up the environment
Ensure the following files are in the project directory:
o	autism_model: The pre-trained CNN model file (compatible with TensorFlow).
o	dataset: A folder containing test images for validation.
5.	Run the Flask app
Start the Flask application using the command:
6.	python app.py
7.	Access the app
Open the app in your web browser at http://localhost:5000.

Project Structure
Machine-Learning-ASD-Detection/
├── app.py Main Flask application code
├── requirements.txt List of required Python libraries
├── autism_model Pre-trained CNN model file
├── dataset/Folder containing test images
├── static/Static files (CSS, images)
├── templates/HTML templates for the web interface
└── README.md Project documentation

Usage
Home Page
•	Provides an overview of the app’s purpose and functionality.
•	Displays instructions on how to use the system.
Detection Page
1.	Upload an image of a child for ASD detection.
2.	Click the "Predict" button to analyze the image.
3.	View the result, including the ASD classification and model accuracy.
Feedback Section
•	Users can submit feedback for further improvement.
•	Feedback is stored for future analysis and model updates.

Dataset and Preprocessing
•	Dataset: Images of children, categorized based on ASD indicators.
•	Preprocessing: 
o	Image resizing, alignment, and cropping.
o	Pixel normalization for uniform input.
o	Data augmentation to enhance model generalization.

Technologies Used
•	Programming Language: Python
•	Machine Learning Framework: TensorFlow, Keras
•	Web Framework: Flask
•	Tools: Jupyter Notebook, Anaconda Navigator

Requirements
Key Python libraries:
•	flask
•	tensorflow
•	numpy
•	opencv-python
•	pillow
Install all dependencies:
pip install -r requirements.txt

Future Enhancements
•	Add multimodal data integration for improved accuracy.
•	Explore advanced architectures like transformers.
•	Deploy as a cloud-based service for scalability.

