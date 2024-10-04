# Emotion Detection Project

A real-time facial emotion detection system that classifies emotions into seven categories: angry, disgusted, fearful, happy, neutral, sad, and surprised. This project utilizes a Convolutional Neural Network (CNN) trained on the FER-2013 dataset to provide accurate emotion predictions from live video feeds.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
- [Model Architecture](#model-architecture)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Real-Time Detection**: Analyze emotions from live webcam feeds.
- **Model Training**: Train the model with custom datasets or use a pre-trained model for immediate predictions.
- **User-Friendly Interface**: Display emotion predictions directly on the video feed.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/emotion-detection.git
cd emotion-detection
pip install -r requirements.txt

# Emotion Detection Project

A real-time facial emotion detection system that classifies emotions into seven categories: angry, disgusted, fearful, happy, neutral, sad, and surprised. This project utilizes a Convolutional Neural Network (CNN) trained on the FER-2013 dataset to provide accurate emotion predictions from live video feeds.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage Instructions](#usage-instructions)
- [Model Architecture](#model-architecture)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Real-Time Detection**: Analyze emotions from live webcam feeds.
- **Model Training**: Train the model with custom datasets or use a pre-trained model for immediate predictions.
- **User-Friendly Interface**: Display emotion predictions directly on the video feed.

## Installation

To get started, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/emotion-detection.git
cd emotion-detection
pip install -r requirements.txt

Usage Instructions
Download the FER-2013 dataset and place it in the src folder.
To train the model, run:
bash
cd src
python emotions.py --mode train

To run the pre-trained model and view predictions, execute:
bash
cd src
python emotions.py --mode display

Model Architecture
The system employs a 4-layer Convolutional Neural Network (CNN) for emotion classification. Face detection is performed using Haar Cascade, resizing detected faces to 48x48 pixels for input into the CNN. The network outputs softmax scores for each emotion class.
Contributing
Contributions are welcome! If you have suggestions or improvements, please create a pull request or open an issue.
License
This project is licensed under the MIT License. See the LICENSE file for details.
