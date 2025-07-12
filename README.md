

## Real-Time Emotion Detection Avatar with Voice Feedback

This project uses **OpenCV**, **MediaPipe**, **NumPy**, and **pyttsx3** to detect facial emotions in real-time from a webcam feed. It overlays an animated face mesh with emotion labels and gives spoken feedback about the detected emotion.

## 🎥 Demo Video

[![Watch the video](https://img.youtube.com/vi/1xhsJ2bMboYSmpmUwsT9CIMvLCGDUkL3x/0.jpg)](https://drive.google.com/file/d/1xhsJ2bMboYSmpmUwsT9CIMvLCGDUkL3x/view?usp=sharing)

Click the image above to watch the demo on Google


### Features

* **Webcam-Based Real-Time Detection**
* **Face Mesh & Iris Tracking**
* **7 Emotions Classified**: Happy, Sad, Angry, Surprise, Fear, Disgust, Neutral
* **Text-to-Speech Feedback** with custom messages for each emotion
* **Threaded TTS Engine** to ensure smooth real-time performance

---

### Libraries Used

* `opencv-python`
* `mediapipe`
* `numpy`
* `pyttsx3`

---

### How It Works

1. **Capture Webcam Feed**
2. **Detect Facial Landmarks using MediaPipe Face Mesh**
3. **Calculate Mouth, Eye & Iris Metrics**
4. **Classify Emotion based on facial ratios**
5. **Overlay Emotion Label and Emoji**
6. **Speak Out Emotion-Specific Message**

---

### How to Run

```bash
# Clone this repo
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>

# Create virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install opencv-python mediapipe numpy pyttsx3

# Run the script
python emotion_avatar.py
```

---

### Notes

* Press **ESC** to exit.
* Uses your default webcam.
* Make sure your system has a microphone/speaker for TTS.
* Tested with Python 3.8+

---

### Example

| Webcam Feed     | Avatar Overlay                 |
| --------------- | ------------------------------ |
| Original Webcam | Face Mesh with Emotion & Emoji |

---

###  Sample Messages

* **Happy**: *"You look happy! You look cute when you smile."*
* **Sad**: *"You seem sad. What happened dear?"*
* **Angry**: *"You look angry! Calm down dear."*
* ...and more!

---

### Credits

Built using **MediaPipe** and **OpenCV**, inspired by human-computer interaction research.

---

### License

Open-source for learning and experimentation. Feel free to fork & enhance!

