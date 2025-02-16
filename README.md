# Computer Vision Projects

This repository contains several Python-based projects that focus on computer vision tasks, including object recognition, color detection, QR code recognition, and camera control. These notebooks leverage popular libraries like OpenCV, TensorFlow, and others to implement image processing and machine learning techniques. The repository also includes an autonomous driving project using Raspberry Pi.

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Notebooks](#notebooks)
- [License](#license)
- [Repository Structure](#repository-structure)
- [References](#references)

## Introduction

This collection of Jupyter notebooks demonstrates various computer vision projects aimed at recognizing and interacting with the physical world using visual data. Some projects focus on color detection, object recognition, and QR code reading, while others explore camera integration and autonomous vehicle applications. This repository serves as a practical guide for building and enhancing computer vision systems.

### Key Projects

- **Color Detection**: Identifies and tracks specific colors in images or video streams.
- **Object Recognition**: Detects and classifies objects in images using machine learning models.
- **QR Code Recognition**: Scans and decodes QR codes from images or live video.
- **Camera Driver**: Interfaces with cameras, capturing images or video feeds.
- **Autonomous Driving**: Implementation of full autonomous driving mode on a prototype car using Raspberry Pi.

---

## Installation

### Prerequisites

Ensure you have the following installed:

- Python 3.6+
- OpenCV
- TensorFlow
- NumPy
- Matplotlib
- Pillow
- PiCamera (for Raspberry Pi users)

To install the dependencies, you can create a virtual environment and run:

```bash
pip install -r requirements.txt
```

Ensure you have `requirements.txt` in the repository, which lists all required dependencies.

---

## Usage

### Running Notebooks

Each project is contained within a Jupyter Notebook. To run them:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/repository-name.git
   ```
   
2. Navigate to the directory:
   ```bash
   cd repository-name
   ```

3. Start Jupyter:
   ```bash
   jupyter notebook
   ```

4. Open the relevant notebook and run the cells to see the implementation.

### Camera Driver

For projects involving camera integration, make sure your camera is properly set up. The **Camera Driver.ipynb** notebook contains the code to interface with cameras and capture images or video.

### Object Recognition

To run the **Object Recognition.ipynb**, ensure that you have the required models and that your environment is set up with the necessary libraries. The notebook uses pre-trained models or custom models to detect and classify objects in images.

### Autonomous Driving

The **Untitled.ipynb** notebook is dedicated to full autonomous driving mode, implementing algorithms for navigation, obstacle avoidance, and decision-making. This project uses Raspberry Pi to control the prototype car autonomously.

---

## Notebooks

Below is a list of the main Jupyter Notebooks included in this repository:

- **Camera Driver.ipynb**: Controls the camera, captures images, and processes video.
- **Color Detection.ipynb**: Detects specific colors in images or video streams.
- **Object Recognition.ipynb**: Detects and classifies objects in images or video.
- **QR Code Recognition.ipynb**: Recognizes and decodes QR codes.
- **circle the color rcgntn.ipynb**: Color recognition with specific circle detection.
- **clr rcgntn-img transmission.ipynb**: Color recognition with image transmission.
- **color follow - img transfr split vrsn.ipynb**: Image processing with color-following algorithms.
- **color follow.ipynb**: Detects colors and follows specific color targets.
- **color rcgntn+button.ipynb**: Color recognition with button control interaction.
- **Untitled.ipynb**: Full autonomous driving mode for prototype car using Raspberry Pi.

Each notebook contains detailed instructions and code for performing the relevant task.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Repository Structure

Here’s an overview of the repository structure:

- **Notebooks/**: Contains all Jupyter notebooks for various computer vision projects.
- **LICENSE**: Contains the project's license information.
- **requirements.txt**: Lists the dependencies required to run the project.

---

## References

1. OpenCV documentation: https://opencv.org/documentation/
2. TensorFlow tutorials: https://www.tensorflow.org/tutorials
3. Raspberry Pi Camera: https://www.raspberrypi.org/documentation/usage/camera/

For additional resources, check out the notebooks themselves and their associated references.

---
