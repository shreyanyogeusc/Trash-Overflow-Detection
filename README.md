# Trash Overflow Detection

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-red.svg)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)
![Hackathon-Winner](https://img.shields.io/badge/Hackathon-USC_MindSpark_Winner-green.svg)

## Overview

The **Trash Overflow Detection Model** leverages Computer Vision and Deep Learning technologies to detect trash overflow conditions in real-time. Using OpenCV for image capture and processing, coupled with Convolutional Neural Networks (CNNs), this project ensures accurate and efficient classification of trash bin overflow, aiming to enhance waste management systems.

### Features
- Real-time image capture and processing using OpenCV.
- Overflow detection and classification using CNN.
- High accuracy and performance tailored for practical deployment.

---

## Dataset

- **Source**: Custom dataset collected during project development.
- **Details**:
  - Total Images: ~500 (collected and labeled during the hackathon).
  - Image Dimensions: Resized to 128x128 pixels for CNN input.
  - Classes: `Overflow` and `Not Overflow`.

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/MalariaCellClassification.git
   cd MalariaCellClassification
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the notebook.

## Usage

### Running the Jupyter Notebook
1. Open `trash_overflow.ipynb` in Jupyter Notebook.
2. Execute the cells to preprocess data, train the model, and evaluate performance.

### Running the Gradio Interface
1. Run the Gradio code in the notebook.
2. Access the web interface via the provided link.
3. Upload a cell image to get predictions.

---

## File Structure

```
trash-overflow-detection/
│
├── dataset/            # Directory for test images
├── src/                                 # Source code
│   ├── trash_overflow.ipynb             # Main notebook
├── README.md               # Project overview
├── requirements.txt        # Python dependencies
├── LICENSE                 # License for the project
└── .gitignore              # Ignore unnecessary files
```
