# GestureVoiceAid

GestureVoiceAid is a real-time hand gesture and facial expression recognition system designed to aid individuals with special needs. It recognizes specific hand gestures and provides vocal feedback using text-to-speech technology.

Supervisor : https://github.com/Anwar-Ali-Sathio
Project Partner: https://github.com/shaharyar4t4

## Features

- Real-time hand gesture recognition using Mediapipe.
- Real-time facial expression recognition using FER.
- Real-time face detection using Face Recognition.
- Text-to-speech conversion for recognized gestures.

## Recognized Gestures

- Hello
- Yes
- No
- Peace
- Thank You
- Help

## Requirements

- Python 3.6+
- OpenCV
- Mediapipe
- FER
- Face Recognition
- Numpy
- Pyttsx3

## Installation

1. Clone the repository:

    ```sh
    git clone https://github.com/MSameer18/GestureVoiceAid.git
    cd GestureVoiceAid
    ```

2. Install the required packages:

    ```sh
    pip install opencv-python mediapipe fer face-recognition numpy pyttsx3
    ```

## Usage

Run the main script to start the real-time feature detection:

```sh
python main.py
