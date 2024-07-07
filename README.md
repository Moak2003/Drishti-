**Drishti - Diabetic Retinopathy Decision Support System**

**Overview**

Drishti is a sophisticated system designed for the early detection and classification of Diabetic Retinopathy (DR) using modern technologies such as Computer Vision and Machine Learning. Leveraging Convolutional Neural Networks (CNNs) and residual networks, Drishti aims to assist healthcare professionals by providing an efficient and scalable solution to detect DR from retinal fundus images.

**Motivation**

The motivation for the Diabetic Retinopathy Decision Support System project stems from the significant global health challenge posed by diabetes and its complications, particularly Diabetic Retinopathy. With an estimated 29.1 million people in India and 347 million people worldwide living with diabetes, the scale of the problem is immense. Diabetic Retinopathy, a condition that affects the eyes of individuals with diabetes, can lead to severe vision loss if not detected and managed early. However, the current process of detecting Diabetic Retinopathy is time-consuming and requires a trained clinician to examine and evaluate digital color fundus photographs of the retina. This manual process may not be scalable given the rising prevalence of diabetes. Therefore, there is a pressing need for a more efficient, automated system for the early detection of Diabetic Retinopathy.

**Objective**

The primary objective of the project is to leverage modern technologies, such as Computer Vision & Machine Learning, to develop an automated system for the early detection of Diabetic Retinopathy. By utilizing image samples of retinas, the system aims to identify signs of Diabetic Retinopathy at an early stage, thereby enabling healthcare professionals to intervene promptly. This could potentially prevent vision loss in people with diabetes and significantly improve their quality of life. Furthermore, the system could also alleviate the workload of clinicians and make the detection process more efficient and scalable. Ultimately, the project aims to contribute to the broader goal of effective disease management in the healthcare domain.

**Features**

Automated Detection: Detects Diabetic Retinopathy from retinal fundus images.
Severity Classification: Classifies the severity of DR into five stages: No DR, Mild, Moderate, Severe, and Proliferative DR.
Efficiency: Reduces the time and effort required for manual screening by clinicians.
Scalability: Provides a scalable solution for large-scale screening programs.
Technology
Programming Language: Python
Frameworks: TensorFlow, Keras
Libraries and Modules: OpenCV, numpy, pandas, scikit-learn, matplotlib, seaborn
Model Architecture: ResNet-152
Literature Review
In recent decades, there has been a significant focus on the investigation of retinal images, particularly in the context of the automated diagnosis of diabetic retinopathy (DR). This attention has led to the development of various methods aiming to detect major DR characteristics, including hemorrhages, microaneurysms, and exudates. The following sections provide a brief overview of the most popular methods in this domain. Read More

**Model Preparation**

**Architecture**
The proposed model for diabetic retinopathy detection adopts a Convolutional Neural Network (CNN) design with a ResNet-152 architecture. This model processes pre-processed retinal fundus images through multiple convolutional layers, pooling layers, and a global average pooling layer, followed by dense layers and a final softmax output layer.

**Working Principle**

Retinal images are preprocessed and fed into the ResNet-152 model, which extracts features and classifies the severity of DR. The model uses residual connections to mitigate the vanishing gradient problem, ensuring effective training.

**Results and Discussion**

**Training Accuracy: 96.01%
Training Loss: 0.136
Validation Accuracy: 93.2%
Test Accuracy: 92.32%
Test Loss: 0.149**

These results highlight the model's robust performance and potential for effective real-world application.

Installation
Clone the Repository

bash
Copy code
git clone https://github.com/Moak2003/Drishti-.git
cd Drishti-
Install the Required Modules

bash
Copy code
pip install -r requirements.txt
Usage
Run the main script to start the detection process:

bash
Copy code
python main.py
Contributing
Contributions are welcome! If you have any suggestions, bug fixes, or new features to propose, please submit an issue or create a pull request.

Fork the Repository

Click on the fork button at the top right corner of the repository page.

Clone the Forked Repository

bash
Copy code
git clone https://github.com/<your-github-username>/Drishti-.git
Make Your Changes

Make the necessary changes in your local repository.

Commit and Push

bash
Copy code
git add .
git commit -m "Your commit message"
git push origin main
Create a Pull Request

Go to the original repository on GitHub and create a pull request.

**Links**
**APTOS Real Time Diabetic Retinopathy Dataset Link - https://www.kaggle.com/datasets/mariaherrerot/aptos2019.**
**Deployed Project on Hugging Face - https://huggingface.co/spaces/idk-who/DRD.**

Thank You.
