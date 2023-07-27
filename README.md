# Automated-Bone-Fracture-Detection
 Automated Bone Fracture Detection System  This GitHub repository contains the code for an automated bone fracture detection system implemented in Python using deep learning techniques. The system is designed to identify bone fractures from medical images with the potential to revolutionize medical diagnostics.
 Functionalities:

Data Collection and Preparation: The system supports the maintenance and organization of image datasets, with separate folders for training, validation, and testing. Each folder contains subfolders for fractured and non-fractured images.

Image Preprocessing and Data Augmentation: Images are preprocessed to ensure uniformity and normalized to improve model training. Data augmentation techniques, such as rotation and flipping, are employed to enhance the model's robustness.

Model Architecture and Training: The deep learning model is built using Convolutional Neural Networks (CNNs) to detect bone fractures. The model is compiled with binary cross-entropy loss and trained using the Adam optimizer.

GUI with Tkinter: The system includes a graphical user interface (GUI) built with Tkinter. The GUI features an "Upload Image" button, allowing users to select an image for examination.

Image Display and Noise Reduction: The uploaded image is displayed to the user using OpenCV. Noise reduction is applied to improve image clarity, enhancing the model's fracture detection accuracy.

Fracture Detection and Report Generation: After uploading the image, users can click the "Generate Report" button. The system processes the image through the trained model and displays the result—either "Fractured" or "Not Fractured."

Model Evaluation: The system evaluates the model's performance on a separate test set, providing metrics such as accuracy, precision, recall, and F1 score.

Model Saving and Deployment: After training, the model can be saved to a file using the .h5 format. This facilitates future use and deployment in medical environments for real-time bone fracture detection.

The system's automation and efficiency can aid medical professionals in early diagnosis and treatment planning, potentially reducing patient wait times and improving overall medical care. This repository aims to promote research and development in the field of automated medical image analysis and its application to bone fracture detection.
