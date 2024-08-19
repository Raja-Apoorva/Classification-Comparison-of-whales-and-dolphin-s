# Classification-Comparison-of-whales-and-dolphin-s

## Overview

The objective of this project is to identify the most effective deep learning architecture for classifying images of whales and dolphins. Using a dataset of 30,000 images, the project includes steps such as data preprocessing, class balancing with augmentation, and training on multiple architectures, including ResNet, VGG16, and AlexNet. The results demonstrate that ResNet outperforms VGG16 and AlexNet by 22% in terms of both R² and cross-validated R² scores.

## Features

- **Data Preprocessing**: Applied necessary preprocessing steps to ensure the dataset is ready for training, including resizing, normalization, and data splitting.
- **Class Balancing**: Addressed class imbalance issues using data augmentation techniques, ensuring the models are trained on a balanced dataset.
- **Model Training**: Trained three different architectures—ResNet, VGG16, and AlexNet—on the dataset.
- **Performance Comparison**: Evaluated model performance using R² and cross-validated R² scores, determining that ResNet outperforms the other architectures by a significant margin.

## Technology Stack

- **Programming Language**: Python
- **Libraries**: 
  - TensorFlow/Keras (for model training and evaluation)
  - NumPy, Pandas (for data handling)
  - OpenCV, PIL (for image processing)
  - Matplotlib, Seaborn (for data visualization)
- **Models Used**:
  - ResNet
  - VGG16
  - AlexNet

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Raja-Apoorva/Classification-Comparison-of-whales-and-dolphin-s.git
   cd Classification-Comparison-of-whales-and-dolphin-s
   ```

2. **Download the Dataset**
   - Obtain the whale and dolphin image dataset (30,000 images) and place it in the `data/` directory.
   - Ensure the dataset is structured correctly for training (e.g., separated into subfolders for each class).

## Usage

- **Data Preprocessing**: Execute `preprocess_data.py` to prepare and augment the dataset.
- **Model Training**: Train the provided models by running `train_models.py`. This script will output performance metrics for each architecture.
- **Performance Evaluation**: Use `evaluate_models.py` to compare the performance of ResNet, VGG16, and AlexNet, focusing on R² and cross-validated R² scores.

## Contributing

If you wish to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Special thanks to the developers of TensorFlow, Keras, and other open-source libraries that made this project possible.
- Gratitude to the providers of the whale and dolphin image dataset.
