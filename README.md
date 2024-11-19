# MNIST Digit Classification with PyTorch

A complete PyTorch-based solution for the MNIST handwritten digit classification challenge, including data exploration, model training, evaluation, and Kaggle submission generation.

## Overview

The MNIST dataset is a collection of 70,000 grayscale images of handwritten digits (0–9). This project solves the multi-class classification problem of identifying the correct digit for each image. It serves as an excellent introduction to deep learning concepts, particularly neural networks.

## Features

- **Data Preprocessing**: Includes normalization and custom PyTorch `Dataset` creation.
- **Exploratory Data Analysis**: Visualizes sample images and provides statistical insights.
- **Deep Learning Model**: Implements a fully connected neural network using PyTorch.
- **Training and Evaluation**: Tracks loss and accuracy with a validation split.
- **Kaggle Submission**: Generates predictions and prepares a CSV for Kaggle competition submission.

## Getting Started

### Prerequisites

- Python 3.8+
- PyTorch 1.12+
- Jupyter Notebook or Kaggle environment

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/MNIST-Digit-Classification-PyTorch.git
   ```
2. Navigate to the project directory:
   ```bash
   cd MNIST-Digit-Classification-PyTorch
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the Notebook**:
   Open `mnist_digit_classification.ipynb` in Jupyter Notebook or directly on Kaggle.
   
2. **Train the Model**:
   Execute the notebook cells to preprocess data, train the model, and evaluate it.

3. **Generate Kaggle Submission**:
   Run the prediction step to create `submission.csv`, ready for upload to Kaggle.

## Repository Structure

```
MNIST-Digit-Classification-PyTorch/
│
├── README.md                       # Project overview
├── mnist_digit_classification.ipynb # Main notebook
├── submission.csv                  # Example Kaggle submission
├── requirements.txt                # Python dependencies
├── src/                            # Optional: modularized code
│   ├── dataset.py                  # Dataset-related code
│   ├── model.py                    # Model architecture
│   └── train.py                    # Training logic
└── LICENSE                         # MIT License
```

## Results

The model achieves an accuracy of **XX.XX%** on the validation set and **XX.XX%** on Kaggle leaderboard submissions.

## Contributing

Contributions are welcome! Please submit a pull request or raise an issue if you find a bug or have suggestions for improvement.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
