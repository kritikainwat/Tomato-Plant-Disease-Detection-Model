# Tomato-Plant-Disease-Detection-Model
Description

This project develops a lightweight machine learning model using TinyML techniques to detect tomato plant diseases from leaf images in real-time. By leveraging TensorFlow Lite and Edge Impulse, the model runs directly on edge devices, providing immediate insights for agricultural decision-making. With a dataset of 16,011 images across 10 disease categories, the model undergoes rigorous preprocessing, augmentation, and optimization. Real-world testing validates its effectiveness, offering farmers a convenient tool for on-site disease diagnosis, potentially revolutionizing agricultural practices.

Shortcomings

Limited Dataset: Despite efforts in augmentation, the dataset may still lack comprehensive representation of environmental factors affecting disease manifestation.

Dependency on Image Quality: The model's performance could be hindered by variations in image quality, such as lighting conditions and camera resolution, impacting its real-world applicability.

Dependency of Connectivity: Connectivity limitations in rural areas hinder timely updates and maintenance, compromising the effectiveness of edge-based disease detection models.

Possible Future Extension

Multi-Crop Expansion: Adapting the model for diverse crops enhances its utility, catering to varied agricultural requirements.

Mobile App Integration: Creating a user-friendly mobile app enables convenient on-the-go disease diagnosis and intervention for farmers.

Sensor Data Integration: Incorporating environmental sensor data enhances disease detection accuracy by considering factors affecting plant health.

Dataset Used Plant Disease

Key Features

Dataset: Plant Village dataset containing 16,011 tomato leaf images across 10 disease categories.

Methodology: Data preprocessing, model development, conversion, deployment, evaluation, and validation.
Results: Achieved accuracy of 89.6% in disease identification.
Expected Outcomes: High-performing, lightweight ML model, successful deployment on edge devices, real-world effectiveness.
Real-World Use: Real-time plant health prediction via the Edge Impulse app on mobile devices.

nput Images

<img width="1599" height="1464" alt="image-1" src="https://github.com/user-attachments/assets/ac8a1291-df3d-4dbc-88c0-f0286dcd24bb" />


Model

<img width="1240" height="405" alt="image" src="https://github.com/user-attachments/assets/f673d7a0-a322-40be-9b48-704a01992363" />

Output

<img width="680" height="680" alt="image-2" src="https://github.com/user-attachments/assets/bec40993-89c0-406d-8e0f-8fbe2675216a" />
<img width="1567" height="1617" alt="image-3" src="https://github.com/user-attachments/assets/e0b7edb4-0f91-4f58-9471-f5d65b994bd7" />
<img width="1639" height="1615" alt="308049890-1b2f2b2a-c3ef-48f3-a90a-2e36dd7352f4" src="https://github.com/user-attachments/assets/0e6eebe8-d251-4fa6-a613-dada5b8277b7" />


Technology Stack

TensorFlow

TensorFlow Lite

Edge Impulse

Python

How to Use

Clone the repository -https://github.com/kritikainwat/Tomato-Plant-Disease-Detection-Model/edit/main/README.md
Download the dataset.
Install required dependencies.
Run the jupiter notebook.
Upload tf_lite_quantized_model.tflite file on Edge Impulse and Build the model.





