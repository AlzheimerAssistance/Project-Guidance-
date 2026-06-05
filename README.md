# Raspberry Pi 5 Setup

## 1. Update System

```bash
sudo apt update
sudo apt upgrade -y
```

## 2. Install Virtual Environment Support

```bash
sudo apt install python3-venv -y
```

## 3. Create Virtual Environment with Raspberry Pi System Packages

```bash
python3 -m venv --system-site-packages venv
```

## 4. Activate Virtual Environment

```bash
source venv/bin/activate
```

## 5. Upgrade Pip

```bash
pip install --upgrade pip
```

## 6. Install Required Python Packages

```bash
pip install ultralytics
pip install torch torchvision
pip install opencv-contrib-python
pip install numpy
pip install SpeechRecognition
pip install pyttsx3
pip install pyaudio
```

## 7. Verify Camera Access

```bash
python3 -c "from picamera2 import Picamera2; print('Camera OK')"
```

## 8. Verify Raspberry Pi Camera

```bash
rpicam-hello
```

## 9. Run the Project

```bash
source venv/bin/activate
python3 main.py
```

# Main Libraries Used

* Picamera2 (Raspberry Pi Camera Interface)
* OpenCV (Computer Vision)
* OpenCV-Contrib (LBPH Face Recognition)
* Ultralytics YOLOv8 (Object Detection & Pose Estimation)
* PyTorch (Deep Learning Backend)
* NumPy (Numerical Computation)
* SpeechRecognition (Speech-to-Text)
* eSpeak / pyttsx3 (Text-to-Speech)

# Project Modules

* Fall Detection using YOLOv8 Pose Estimation
* Family Member Recognition using Haar Cascade + LBPH
* Medication Reminder using Voice Interaction
* Patient Tracking and Monitoring
* Voice-Based Communication System
* Emergency Alert System
* Smart Caregiver Assistant
