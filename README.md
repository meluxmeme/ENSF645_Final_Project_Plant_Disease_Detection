# ENSF645 Final Project: Plant Disease Detection

This repository contains the source code and resources for the ENSF645 Final Project on Plant Disease Detection. The project utilizes deep learning techniques to accurately identify diseases in plants, providing an automated diagnostic tool beneficial for agricultural applications.

## Project Overview
The primary objective of this project is to leverage machine learning models, specifically deep neural networks, to detect and classify diseases from images of plants. This solution assists farmers and agricultural specialists in early detection and timely interventions to improve crop yield and overall plant health.

## Dataset
The dataset used for training and evaluating the models is the **PlantVillage Dataset**, which is publicly accessible through Kaggle. The dataset includes images of healthy and diseased plant leaves across various species.

- **Kaggle Dataset:** [PlantVillage Dataset](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset/code)
- **TALC Dataset Path:** `/work/TALC/enel645_2025w/plant_dataset`

## Project Structure
```
.
├── data/                   # Contains dataset files
├── models/                 # Stores trained model files
├── notebooks/              # Jupyter notebooks for exploratory analysis
├── scripts/                # Scripts for preprocessing, training, and evaluation
├── results/                # Outputs from model evaluations and predictions
└── README.md               # Project documentation
```

## Getting Started

### Prerequisites
Ensure you have the following installed:
- Python 3.8+
- TensorFlow or Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib

### Installation
Clone this repository:
```bash
git clone https://github.com/meluxmeme/ENSF645_Final_Project_Plant_Disease_Detection.git
cd ENSF645_Final_Project_Plant_Disease_Detection
pip install -r requirements.txt
```

### Usage
- **Training the model:**
```bash
python scripts/train_model.py
```

- **Predicting diseases from images:**
```bash
python scripts/predict.py --image_path path/to/image.jpg
```

## Authors
- Lana Oreoluwa
- Laxmi Paudel
- Ayodele Oluwabusola
- Taiwo Oyewole  

