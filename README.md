# Driver Drowsiness Detection System

## Overview

The Driver Drowsiness Detection System is designed to enhance road safety by detecting drowsiness in drivers and alerting them in real-time. This project utilizes computer vision techniques to monitor the driver's eyes for signs of drowsiness. When drowsiness is detected, the system triggers an alert to prompt the driver to take necessary actions.

## Installation

1. Clone this repository to your local machine:

    ```sh
    git clone https://github.com/ChaitanyaChilukuri663/Driver_Drowsiness_Detection.git
    ```

2. Install the required dependencies:

    ```sh
    pip install opencv-python dlib scipy pydub simpleaudio
    ```

3. Download the pre-trained facial landmark predictor file 'shape_predictor_68_face_landmarks.dat' from the [dlib website](http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2) and place it in the project directory.

## Usage

1. Navigate to the project directory:

    ```sh
    cd driver-drowsiness-detection
    ```

2. Run the drowsiness detection script:

    ```sh
    python drowsiness_detection.py
    ```

3. The system uses your webcam to capture video frames and analyze the driver's eyes for drowsiness.

4. If the driver's eyes are closed for an extended period, an audible alert will play.

5. Press the 'Esc' key to exit the application.

## Dependencies

- OpenCV (opencv-python)
- dlib
- scipy
- pydub
- simpleaudio

## Acknowledgments

This project is based on the concept of driver drowsiness detection and utilizes various open-source libraries and resources. Special thanks to the developers and contributors of these libraries for their valuable contributions.

