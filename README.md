# Emotion Recognition with FER2013
This project uses deep learning and computer vision to recognize human emotions in real time from facial expressions using the FER2013 dataset: https://www.kaggle.com/datasets/msambare/fer2013

## Project Overview
Built and trained a custom CNN model for emotion classification (7 classes)

Dataset: FER2013 (grayscale 48x48 facial images)

Real-time detection using webcam and OpenCV

Face detection via Haar cascades

Final model achieves ~50–53% accuracy on validation data

## Notebooks
data_loading_and_exploration.ipynb : Class distribution, image samples, and average face visualization

model_training.ipynb : CNN model training with Keras, plotted training/validation curves

real_time_detection.ipynb : Live webcam demo with face detection and emotion classification

## Requirements
To install the required packages, run:
pip install opencv-python tensorflow matplotlib

## How to Run
Clone the repo:
git clone https://github.com/tshehadey/emotion-recognition-cv.git
cd emotion-recognition-cv

Run the real-time detection notebook:

Open the file named real_time_detection.ipynb

Make sure the file final_emotion_model.keras is in the same folder

Note: When you run the notebook, the webcam window may not pop up automatically.
You might have to click the OpenCV program icon on the bottom taskbar to bring it to the front.

Press the "q" key to exit the webcam loop.




