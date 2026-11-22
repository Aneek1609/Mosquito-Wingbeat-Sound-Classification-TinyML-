# 🦟 Mosquito Wingbeat Sound Classification using TinyML

## Overview

This project explores the use of **TinyML (Tiny Machine Learning)** and embedded systems for audio-based mosquito wingbeat sound classification. The system uses a machine learning model trained for audio classification and deploys it on an **Arduino Nano**, allowing inference to run directly on embedded hardware rather than relying on a computer or cloud-based processing.

The project demonstrates the application of machine learning in resource-constrained environments and explores the potential of sound-based analysis for mosquito detection.

## 🎯 Objectives

- Explore machine learning for mosquito wingbeat sound classification.
- Deploy a trained audio classification model on a microcontroller.
- Implement TinyML inference on Arduino Nano hardware.
- Explore edge computing for real-time audio processing applications.
- Demonstrate the integration of AI models with embedded systems.

## ⚙️ Technologies Used

- **Programming:** C/C++, Python
- **Hardware:** Arduino Nano
- **Machine Learning:** TinyML, Audio Classification
- **Model Deployment:** Edge Impulse
- **Embedded AI:** On-device inference

## 🔬 Project Workflow

1. **Audio Classification Model** – Use a trained machine learning model designed for sound classification.
2. **Model Deployment** – Export the trained model using the Edge Impulse Arduino deployment workflow.
3. **Hardware Integration** – Integrate the inference library into the Arduino-based embedded system.
4. **On-device Inference** – Execute the machine learning inference on the microcontroller.
5. **Sound Analysis** – Use audio input to perform mosquito wingbeat sound classification.

## 🧠 TinyML Implementation

The project utilizes TinyML to bring machine learning inference to low-power embedded hardware. The model is packaged as an Edge Impulse inference library, enabling its integration into an Arduino development environment.

Instead of processing data entirely on a computer, the embedded device can execute the deployed model locally, demonstrating the principles of edge AI and embedded machine learning.

## 🔌 Hardware

- Arduino Nano
- Audio input / microphone hardware compatible with the audio acquisition setup
- Connecting wires
- USB cable for programming and power

## 💻 Software & Libraries

- Arduino IDE
- Edge Impulse generated inference library
- Arduino-compatible C/C++ environment

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Install Arduino IDE

Download and install Arduino IDE from:

https://www.arduino.cc/en/software

### 3. Import the Edge Impulse Library

- Open Arduino IDE.
- Navigate to **Sketch → Include Library → Add .ZIP Library**.
- Select the Edge Impulse inference library ZIP included in the project.
- Wait for the library to be imported.

### 4. Connect the Arduino Nano

- Connect your Arduino Nano to your computer using USB.
- Select the appropriate Arduino board from **Tools → Board**.
- Select the correct COM port under **Tools → Port**.

### 5. Upload the Firmware

Open the Arduino sketch included in the repository, configure the required audio input and board settings, compile the program, and upload it to the Arduino Nano.

## 📊 Applications

- Mosquito sound detection research
- Audio-based insect monitoring
- TinyML experimentation
- Embedded machine learning
- Edge AI applications
- Low-resource environmental sensing

## 🌱 Future Improvements

- Improve classification performance with more diverse audio samples.
- Test the system in different environmental noise conditions.
- Optimize model memory usage and inference speed.
- Integrate a dedicated microphone and improve audio acquisition.
- Extend the system to classify additional insect sounds.
- Explore battery-powered operation for portable monitoring.

## 👨‍💻 Author

**Aneek Kumar Sinha**

Machine Learning | AI | Embedded Systems | TinyML

---

⭐ If you find this project interesting, feel free to explore the repository and contribute ideas.
