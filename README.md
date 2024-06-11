# ML-Based Music Genre Predictor

## Overview

This project leverages machine learning to accurately predict song genres, similar to the technology used by popular music platforms like Spotify, Apple Music, and YouTube Music. Whether it's calm music for studying, energetic tunes for exercising, or music for everyday activities, this tool helps in categorizing and recommending music efficiently. The project was completed in the Spring of 2024 under CS 4641 at the Georgia Institute of Technology.

## Key Features

- **Deep Q Network**: Utilizes reinforcement learning to train a Deep Q Network for genre prediction.
- **Bayesian Networks**: Evaluates song novelty and audio content for accurate classification.
- **Neural Networks with Filtering**: Combines neural networks and advanced filtering techniques for enhanced genre prediction accuracy.

## Background

Music platforms have explored various algorithms to enhance user experience by providing accurate music recommendations. Our project dives into:

- **Deep Q Network**: Training methodologies and application in music genre prediction.
- **Bayesian Networks**: Assessment of song novelty and audio content.
- **Neural Networks**: Integration with filtering techniques for improved results.

## Technologies Used

- **Python**: Core programming language for implementing machine learning models.
- **TensorFlow / PyTorch**: Libraries for building and training neural networks.
- **Librosa**: Audio analysis and music processing.
- **Scikit-Learn**: Traditional machine learning algorithms and evaluation metrics.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Python 3.6+
- TensorFlow / PyTorch
- Librosa
- Scikit-Learn

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ML-Music-Genre-Predictor.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ML-Music-Genre-Predictor
    ```
3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1. Prepare your dataset and place it in the `data/` directory.
2. Run the training script:
    ```bash
    python train.py
    ```
3. Predict song genres using the trained model:
    ```bash
    python predict.py --input songfile.mp3
    ```

## Results

Our model demonstrates a high accuracy rate in predicting song genres, making it a viable solution for integration into music recommendation systems.

## References

1. Training a Deep Q Network
2. Bayesian Networks for Song Novelty and Audio Content Evaluation
3. Neural Networks with Filtering Techniques

## Contributing

We welcome contributions to improve our project. Feel free to fork the repository and create pull requests.

## License

This project is licensed under the MIT License.

## Contact

For more information, please contact [your-email@example.com](mailto:your-email@example.com).

---

We invite you to explore our project in more detail and contribute to its development!

