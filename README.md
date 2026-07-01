# Conser-vision Practice Area: Wildlife Image Classification

Deep Learning image classification project developed for the **DrivenData Conser-vision Practice Area** competition.

The objective is to automatically classify wildlife species captured by camera traps installed in Taï National Park, helping conservation researchers process thousands of images efficiently using Computer Vision techniques.

## Dataset

The dataset used in this project is provided by the Wild Chimpanzee Foundation through the DrivenData Conser-vision Practice Area competition.

The dataset is free to use for learning and research purposes with proper attribution.

The dataset is **not redistributed** in this repository. Please download it directly from the official competition page.

### Citation

The Pan African Programme: The Cultured Chimpanzee, Wild Chimpanzee Foundation, DrivenData. (2022). *Conser-vision Practice Area: Image Classification*. Retrieved July 1, 2026 from https://www.drivendata.org/competitions/87/competition-image-classification-wildlife-conservation/

## Project Overview

Camera traps are widely used in wildlife conservation because they can monitor animal populations with minimal human interference. However, they generate an enormous number of images that require manual inspection.

This project develops a multi-class image classification model capable of identifying the animal species present in each image, including images where no animal appears.

## Problem Type

* Computer Vision
* Deep Learning
* Image Classification
* Multi-class Classification
* Supervised Learning

## Dataset

The dataset consists of camera trap images collected in Taï National Park.

Each sample includes:

* Image (.jpg)
* Image ID
* File path
* Capture site

The target consists of eight mutually exclusive classes:

* antelope_duiker
* bird
* blank
* civet_genet
* hog
* leopard
* monkey_prosimian
* rodent

> **Note:** The dataset is **not included** in this repository. It must be downloaded directly from the official DrivenData competition page in accordance with the competition rules.

## Project Structure

```text
├── data/
├── notebooks/
├── src/
│   ├── datasets/
│   ├── models/
│   ├── training/
│   ├── evaluation/
│   └── utils/
├── outputs/
├── models/
├── requirements.txt
├── README.md
└── LICENSE
```

## Technologies

* Python
* PyTorch
* Torchvision
* TIMM
* Albumentations
* OpenCV
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## Methodology

The project follows a complete Deep Learning workflow:

1. Dataset exploration
2. Exploratory image analysis
3. Class distribution analysis
4. Site-based validation strategy
5. Image preprocessing
6. Data augmentation
7. Transfer Learning
8. Model training
9. Hyperparameter tuning
10. Model evaluation
11. Submission generation

## Model Features

* Transfer Learning
* Data Augmentation
* Multi-class Classification
* Cross Entropy Loss
* Site-aware validation
* Probability prediction for each class

## Evaluation Metric

The competition uses **Multi-class Log Loss**, which evaluates both prediction accuracy and probability calibration.

Lower values indicate better model performance.

## Repository Status

This project is currently under active development.

Future improvements include:

* EfficientNet models
* ConvNeXt
* Vision Transformers (ViT)
* Swin Transformer
* Test Time Augmentation (TTA)
* Model Ensembling
* Hyperparameter Optimization

## Results

Results will be updated as experimentation progresses.

## Competition

DrivenData — Conser-vision Practice Area: Image Classification

## License

This repository is released under the MIT License.

## Author

**Fernando Rioseco**

Data Science | Machine Learning | Artificial Intelligence

Portfolio: https://fernandorioseco.es

GitHub: https://github.com/fer78

