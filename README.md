# Anomaly-detection-in-Traffic-Signs-Recognition

Installation Guide
This guide covers setting up and installing the code for anomaly detection in traffic signs recognition.

Requirements
The code has been developed and tested on Python 3.7. The following packages are required:

PyTorch >= 1.7
OpenCV
Albumentations
Matplotlib
NumPy
An NVIDIA GPU is strongly recommended for model training.

nstallation
Clone the repository:
<!---->
git clone https://github.com/Qurat5/Anomaly-detection-in-Traffic-Signs-Recognition.git

2.  Install the required packages:
<!---->
pip install -r requirements.txt

3.  Download the dataset from [LINK] and extract it into the data folder. The folder structure should be:

<!---->

4.  Train the YOLOv8 model:
<!---->
python train_yolov8.py


5.  Train the autoencoder model:
<!---->
python train_autoencoder.py

6.   Evaluate the models:
<!---->
python evaluate.py
