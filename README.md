# Facial Emotion Recognition with Music Player

This repository contains code for a system that performs facial emotion recognition using a Convolutional Neural Network (CNN) and a simple music player based on the detected emotions.

## Overview

The code is divided into two main parts:

1. **Facial Emotion Recognition (emotions.py):**
    - Utilizes OpenCV for face detection and the pre-trained CNN model for emotion recognition.
    - Displays real-time video with emotion labels and writes detected emotions to 'emotion.txt'.
    - Plays music based on the detected emotion using the music player.

2. **Music Player (musicplayer.py):**
    - Uses Tkinter for the graphical user interface.
    - Integrates VLC for audio playback.
    - Supports basic functionalities such as play, pause, stop, next, shuffle, and displays the playlist.

## Requirements

- Python 3.x
- OpenCV
- TensorFlow
- Keras
- VLC Python bindings
- Matplotlib
- NumPy

Install the required libraries using the following command:

```bash
pip install opencv-python tensorflow keras python-vlc matplotlib numpy

**## How to run**
1.Ensure you have the required libraries installed.

2.Place your music files in the 'songs' directory, organized by emotion categories.

3.Run the facial emotion recognition script:
  python emotion_detection.py
4.The music player will launch, and based on the detected emotion, it will play corresponding songs.
