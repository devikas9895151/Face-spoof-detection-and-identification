# Face Spoof Detection and Identification using CLIP 

An AI-powered face authentication system that performs **face spoof detection** and **person identification** using deep learning techniques. The project uses **RetinaFace**, **DeepFace**, and **CLIP** models to detect faces, verify whether the face is real or spoofed, and identify the person from images or videos.

## Features

* 🔍 Face Detection & Alignment using RetinaFace
* 🛡️ Spoof Detection (Real vs Fake Face Detection)
* 🧠 Person Identification using DeepFace embeddings
* 🎥 Supports image and video input
* ⚡ GPU acceleration with PyTor


  https://github.com/user-attachments/assets/cafc13df-8c33-4510-b97d-c7da582fa3eb

* 📊 Visualization of detection results

## Tech Stack

* Python
* OpenCV
* PyTorch
* DeepFace
* RetinaFace
* OpenAI CLIP
* ONNX Runtime

## Use Cases

* Secure authentication systems
* Smart attendance systems
* Anti-spoofing verification
* AI-based surveillance applications

## Limitations / Drawbacks

* High-quality spoof images or replay attacks may still fool the identification system.
* If spoof detection is not enforced before identification, unauthorized access can occur.
* Access should only be granted when the detected face is verified as **real** and not spoofed.
* Performance may reduce under poor lighting, motion blur, or low-quality video conditions.
* Advanced spoofing methods such as deepfakes or realistic masks can affect accuracy.
