# Advanced-Lane-Detection-and-Object-Detection-ADAS-
Lane Detection + Object Detection

This project combines Lane Detection and Object Detection to build a simplified perception pipeline for autonomous driving. The goal is to detect lane lines on the road and identify surrounding vehicles, ensuring safer navigation for self-driving systems.

📖 You can also refer to my research paper published on IEEE Xplore: Pairing Lane Detection with Object Detection
 -- https://ieeexplore.ieee.org/document/10392267

🔹 Motivation

Autonomous vehicle safety heavily relies on accurate perception. While deep learning models like YOLO exist, this project focuses on developing the pipeline from scratch using computer vision and classical ML techniques to strengthen algorithmic understanding.

🔹 Features
🛣 Lane Detection

Camera calibration & distortion correction

Binary thresholding with Sobel & color transforms

Perspective transform to bird’s-eye view

Polynomial fitting for lane boundaries

Lane curvature & vehicle position estimation

🚘 Object Detection

HOG feature extraction

SVM classifier (Car vs Non-Car)

Sliding window search + HOG subsampling

Heatmaps & thresholding to remove false positives

Bounding box visualization

🔹 Tech Stack

Language: Python

Libraries: OpenCV, NumPy, Matplotlib, Scikit-learn

Algorithms: Sobel Filters, Perspective Transform, Polynomial Fitting, HOG + SVM

📌 Usage
# Clone repo
git clone https://github.com/yourusername/Lane_Object_Detection.git  

# Install dependencies
pip install -r requirements.txt  

# Run pipeline
python main.py
