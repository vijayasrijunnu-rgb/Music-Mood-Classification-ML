# Advancements in Music Mood Classification Machine Learning Techniques for Mood Analysis

# Overview

This project presents an emotion-based music recommendation system that detects a user's facial emotion from an image and recommends music based on the detected mood.

The system uses OpenCV for face detection and a Deep Learning model for emotion recognition. Based on the predicted emotion, relevant songs are displayed and can be played directly through the application.

---

# Features

- Upload facial image
- Detect face using OpenCV
- Predict emotion using Deep Learning
- Recommend songs based on detected mood
- Play songs directly from the application
- Simple and user-friendly GUI

---

# Emotions Supported

- Angry
- Disgust
- Scared
- Happy
- Sad
- Surprised
- Neutral

---

# Technologies Used

- Python
- OpenCV
- TensorFlow
- Keras
- NumPy
- Tkinter
- Playsound

---

# Project Structure

```text
Music_Mood_Classification/
│
├── music_mood_classifier.py
├── README.md
├── requirements.txt
├── .gitignore
│
├── models/
│   ├── haarcascade_frontalface_default.xml
│   └── _mini_XCEPTION.106-0.65.hdf5
│
├── songs/
│   ├── angry.mp3
│   ├── disgust.mp3
│   ├── happy.mp3
│   ├── neutral.mp3
│   ├── sad.mp3
│   ├── scared.mp3
│   └── surprised.mp3
│
├── images/
│
├── screenshots/
│
├── MAJOR -FINAL.pdf
└── MAJOR ppt.pptx
```

---

# Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

# Run the Project

```bash
python music_mood_classifier.py
```

---

## Workflow

1. Upload an image containing a face.
2. Detect the face from the image.
3. Predict the emotion using the trained Deep Learning model.
4. Display songs related to the detected emotion.
5. Select and play a song.

---


# Additional Resources

The file `media.zip` contains:

- images
- models
- songs

Extract the ZIP file into the project directory before running the application.


# Team Project

This project was developed as a team project by four Computer Science Engineering students as part of a B.Tech Major Project (2024–2025).

---

# Future Enhancements

- Real-time webcam emotion detection
- Multiple song recommendations per emotion
- Spotify/YouTube integration
- Improved emotion classification accuracy
- Mobile application support

---

# License

This project is intended for academic and educational purposes.
