# Human Detection with MobileNet SSD

This project implements a human detection system using the MobileNet SSD model. The code processes video streams or images to detect humans in real-time, utilizing several modular components such as preprocessing, detection, and postprocessing.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Code Overview](#code-overview)
- [License](#license)
- [Contributors](#contributors)

## Introduction

The `Human Detection` project is designed to detect humans in video streams using a MobileNet SSD model. The detection process involves reading frames from a video stream, detecting human presence, and drawing bounding boxes around detected individuals. The processed video is then saved to an output file.

## Features

- **Human Detection:** Detects humans in video streams using the MobileNet SSD model.
- **Real-time Processing:** Processes video frames in real-time.
- **Modular Design:** Uses separate modules for preprocessing, detection, and postprocessing.
- **Configurable Input:** Supports both video file and live stream input.

## Installation

To run this project, ensure you have the following dependencies installed:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/MahnazRazavi/Realtime-human-detection.git
   cd Realtime-human-detection
2. **Install required packages:**

Ensure you have Python 3.6 or higher and install the required packages:

   ```bash
   pip install opencv-python


