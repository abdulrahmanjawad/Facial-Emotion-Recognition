# Emotion Detection
An emotion detection CNN model created using TensorFlow that can classify 7 emotions from facial expression images.

# Getting Started
Make sure [Python 3](https://www.python.org/downloads/) is already installed.

## Setting up the environment
 1. Clone or download the repository on your local machine.
 2. Within the Emotion-Detection directory create a Virtual Python Environment with command `python -m venv emotion` where `emotion` is the name of the environment.
 3. Activate the enviroment using the command:
      ```bash
      emotion\scripts\activate
      ```
 4. Install the required packages using:
      ```bash
      pip install -r requirements.txt
      ```
      
## Using the the detector on images
 1. Use `cd` command to move into the detection directory
 2. To detect emotion, use the following command:
    ```bash
    python detector.py image.png
    ```
    Where, `image.png` is the image passed to the detector
    
# Dataset
Facial Emotion Recognition [fer2013](https://www.kaggle.com/msambare/fer2013) was used to train the model.
The data consists of 48x48 pixel grayscale images of faces and has classified 7 emotions (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).
    
# Tools used:
1. Python
2. TensorFlow
3. OpenCV
4. Numpy
5. Argsparse
    
