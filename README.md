<!-- Project Title -->
<h1 align="center">Speech Emotion Classifier</h1>

<!-- Project Overview -->
<p align="center">
  Explore emotions in audio with the TESS dataset and build an advanced emotion classifier.
</p>

<!-- Badges -->
<p align="center">
  <img src="https://img.shields.io/badge/Made%20with-Python-blue" alt="Made with Python">
</p>

<!-- Table of Contents -->
## Table of Contents

- [About the Project](#about-the-project)
- [Dataset Description](#dataset-description)
- [Acknowledgments](#acknowledgments)
- [Code Overview](#code-overview)
- [Usage](#usage)
- [Results](#results)
- [License](#license)

<!-- About the Project -->
## About the Project

Unravel the essence of human emotions through audio data using the Toronto Emotional Speech Set (TESS) dataset. This project aims to create a robust emotion classifier from high-quality audio recordings, offering valuable insights into the world of emotional AI.

<!-- Dataset Description -->
## Dataset Description

### Toronto Emotional Speech Set (TESS)

- **Emotional Diversity:** TESS contains 2800 audio recordings, each featuring two female speakers. These speakers portray 200 target words in seven distinct emotions: anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral.

- **Age and Gender Diversity:** The dataset showcases emotions across a spectrum, as actresses aged 26 and 64 lend their voices, contributing to a diverse and inclusive representation.

- **Audio Format:** All audio files are provided in the WAV format, ensuring compatibility with various machine learning and audio analysis tools.

- **Structured Organization:** TESS is meticulously organized, with audio files categorized by actresses and their corresponding emotions, simplifying data retrieval and analysis.

- **Link :** https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess

### Acknowledgments

A heartfelt thank you to the University of Toronto for curating the TESS dataset. This invaluable resource empowers emotion classification and voice analysis, advancing the realm of emotional AI.

<!-- Code Overview -->
## Code Overview

This repository houses code for various stages of the project, including:

- **Data Exploration:** Dive into the dataset, preprocess the audio, and conduct in-depth analysis and visualization.

- **Feature Extraction:** Utilize Mel-frequency cepstral coefficients (MFCC) and other audio features to enhance emotion recognition.

- **Model Development:** Implement Long Short-Term Memory (LSTM) neural networks for building an effective emotion classifier.

- **Model Training:** Train the model on the TESS dataset, refining its ability to recognize emotions.

- **Result Analysis:** Visualize and interpret the results to gauge the model's performance.

<!-- Usage -->
## Usage

To harness the capabilities of this project and explore the TESS dataset, follow these steps:

1. **Clone the Repository:** Clone this repository to your local machine to access the code and data.

2. **Install Dependencies:** Ensure you have the required Python libraries by running:

<i>pip install -r requirements.txt</i>


<!-- Results -->
## Results
The emotion classifier trained on the TESS dataset achieved remarkable accuracy, with an initial accuracy of 67.0%. Keep in mind that as the dataset size increases and with further model optimization, the accuracy is expected to improve over time, enhancing the model's capability to recognize emotions from audio data.

<!-- License -->
## License
This project is open-source and is licensed under the MIT License. For detailed licensing information, please see the LICENSE file.
