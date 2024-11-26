# ASL Sign Language Detection using YOLOv5

This project implements a sign language detection system using the YOLOv5 object detection framework. The goal is to recognize American Sign Language (ASL) signs from images and videos, enabling better communication with the hearing-impaired.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Training](#training)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

---

## Project Overview

Sign language recognition is an essential task in human-computer interaction and assistive technologies. This project uses YOLOv5 to detect and classify hand gestures representing ASL signs from A-Z.

---

## Features

- **Custom ASL Dataset**: Labeled dataset with images of hand signs for the English alphabet (A-Z).
- **State-of-the-Art YOLOv5**: Advanced object detection architecture for accurate and fast predictions.
- **Real-Time Detection**: Capable of recognizing signs in real-time using a webcam or video feed.
- **Easy Deployment**: Lightweight and easy to set up for research or practical applications.

---

## Dataset

The dataset consists of images labeled with bounding boxes for ASL signs. It is organized into:
- **Training Data**: For model training.
- **Validation Data**: For model validation.
- **Test Data**: For performance evaluation.

**Source**: [Roboflow ASL Dataset](https://roboflow.com)

---


### Prerequisites
- Python 3.8 or higher
- PyTorch 1.7 or higher
