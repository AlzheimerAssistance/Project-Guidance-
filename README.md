# Project-Guidance-

Raspberry Pi 5 Environment Setup

Install Raspberry Pi OS (64-bit) on Raspberry Pi 5.

1)
Update the system packages:
sudo apt update
sudo apt upgrade -y

2)
Install Python development tools:
sudo apt install python3-pip python3-venv -y

3)
Create a dedicated Python virtual environment:
python3 -m venv venv

4)
Activate the virtual environment:
source venv/bin/activate

5)
Upgrade pip inside the virtual environment:
pip install --upgrade pip

6)
Install OpenCV and required computer vision libraries.
Install NumPy for numerical computations.
Install Picamera2 library for Raspberry Pi camera integration.
Install PyTorch and TorchVision for AI model execution.
Install Ultralytics package for YOLOv8-based object detection and pose estimation.
Install MediaPipe for human pose and landmark processing (if used).
Install SpeechRecognition for speech-to-text functionality.
Install eSpeak / pyttsx3 for text-to-speech feedback.
Install Bluetooth audio support for wireless speaker output.
Configure and test the Raspberry Pi Camera Module.
Verify all libraries and hardware components before running project modules.



7)
Project Execution

Activate the virtual environment:
source venv/bin/activate



