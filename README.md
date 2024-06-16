 Flower Classification Project

 Overview

This project involves the classification of flower images into seven distinct categories: commondaisy, tulip, rose, sunflower, dandelion, coreopsis, and water lily. The dataset used for this project is the "Flowers Organized" dataset available on Kaggle. It contains a total of 7,061 images, each of 320x240 pixels resolution, with approximately 800 images per class.

Dataset

Total Images: 7,061
Image Resolution: 320x240 pixels
Classes:'common_daisy': 0, 'coreopsis': 1, 'dandelion': 2, 'rose': 3, 'sunflower': 4, 'tulip': 5, 'water_lily': 6
Data Split: 80% Training, 20% Validation

Models and Results

Three Convolutional Neural Network (CNN) models were trained on this dataset:

1. VGG16
   Validation Accuracy: 92%
2. InceptionV3
   Validation Accuracy: 94.58%
3.MobileNet
   Validation Accuracy: 95.39%

Project Structure

The project is organized as follows:

 `data/`: Contains the flower dataset.
 `notebooks/`: Jupyter notebooks with detailed steps for data preprocessing, model training, and evaluation.
 `models/`: Saved models and their weights.
 `scripts/`: Python scripts for data processing, training, and evaluation.
`results/`: Results of model evaluation including accuracy and loss plots.
`README.md`: Project description and instructions.

Instructions

1. Clone the Repository:
   ```bash
   git clone https://github.com/yourusername/flower-classification.git
   cd flower-classification
   ```

2. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run Jupyter Notebooks:
   Navigate to the `notebooks/` directory and run the Jupyter notebooks to see the data preprocessing, model training, and evaluation steps.

4. Training and Evaluation:
   Use the scripts in the `scripts/` directory to train the models and evaluate their performance.

Conclusion

This project demonstrates the effective use of CNN models for image classification tasks. The best-performing model, MobileNet, achieved a validation accuracy of 95.39%. These models can be further optimized and used for real-world applications in flower classification and beyond.
