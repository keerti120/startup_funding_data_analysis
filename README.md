---



🌿 Plant Leaf Ayurvedic Classification



A Machine Learning project to identify and classify Ayurvedic plant leaves from images. This project uses image processing and classification algorithms to recognize medicinal plants based on their leaf patterns.





---



📌 Features



Automatic Leaf Detection – Reads images and extracts key features.



Ayurvedic Plant Classification – Predicts plant name and category.



Easy to Train – Includes scripts for training and retraining the model.



GUI Interface – Simple and user-friendly interface.



Batch Prediction – Can process multiple images at once.







---



📂 Project Structure



File Name	Description



Main.py	Main GUI application for leaf detection and classification.

Train.py	Script for training the ML model.

front.png	Frontend image used in the GUI.

run.bat	Batch file to start the main program.

runTrain.bat	Batch file to train the model.

README.md	Project description file.







---



📊 Dataset



The dataset contains Ayurvedic plant leaves such as:



Aloevera

Curry

Guava







Each plant category has multiple images taken from different angles and lighting conditions.





---



🧠 Model Details



Algorithm Used: CNN (Convolutional Neural Network)



Frameworks: TensorFlow / Keras



Accuracy Achieved: 92% (on test data)



Image Preprocessing: Resizing, Normalization, and Augmentation using OpenCV







---



⚙ Installation & Requirements



Install required Python libraries:



pip install -r requirements.txt



Example requirements.txt:



tensorflow

opencv-python

numpy

pandas

matplotlib



Identification of Ayurvedic Medicine Plants Based on Leaf

Abstract

The identification and classification of Ayurvedic medicinal plants are vital for their proper application in natural and traditional treatments. This project proposes a deep learning-based system that automatically identifies various Ayurvedic plants using their leaf images. It employs Convolutional Neural Networks (CNN) in combination with Gray-Level Co-occurrence Matrix (GLCM) texture features to enhance classification accuracy. The system extracts comprehensive color, texture, and statistical features from leaf images, followed by classification into specific plant categories such as Neem, Tulsi, Aloe Vera, and more. The model is trained and tested using a custom dataset, achieving high accuracy through optimized feature extraction and CNN architecture. A graphical user interface (GUI) is developed to facilitate real-time prediction using either uploaded leaf images or live webcam feeds, enhancing usability for researchers and practitioners in the herbal medicine domain.

Keywords

Ayurvedic plants, medicinal leaf classification, Convolutional Neural Network, GLCM features, texture analysis, image processing, deep learning, herbal plant recognition, GUI, webcam prediction, Python, CNN, feature extraction



---
