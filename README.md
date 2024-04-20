# Ripe Strawberries Object Detection

## Introduction

Welcome to the Ripe Strawberries Object Detection project! As a Data Science Intern, I've worked on developing a model to detect ripe strawberries in images. This README will guide you through the project details, data sources, implementation procedure, and results.

## Data Source

The dataset used for this project can be found on Kaggle: [Ripe Strawberries Detection](https://www.kaggle.com/datasets/trainingdatapro/ripe-strawberries-detection)

## Implementation Links

- [Roboflow Deployment](https://app.roboflow.com/rrc/ripe-raspberry-detection/deploy)
- [Google Colab Notebook](https://colab.research.google.com/drive/1LNyfKhu8w999w7Ac9J6jaj_sBdqDQN-a?usp=sharing)
- [Implementation Videos](https://drive.google.com/drive/folders/1chIC6jNUib77htK8IJqqgVUlOfWZgRx6?usp=sharing)

## Similar Project Implementation

For reference, here's a similar project on Vehicle Detection:

- [Colab Link](https://colab.research.google.com/drive/17xluuEYIiYImu30gaO-o__umvER7qofi?usp=sharing)

## Dataset Information

The Ripe Strawberries Object Detection dataset consists of images of strawberries aimed at identifying and recognizing ripe berries.

## Procedure & Implementation

1. **Dataset Preparation**: Downloaded the dataset from Kaggle and uploaded it to Roboflow.

2. **Image Annotation**: Annotated images using bounding boxes on Roboflow, labeling ripe strawberries.

3. **Dataset Augmentation**: Augmented the dataset by generating new images through flipping and adding noise, resulting in an increased dataset size from 40 to 96 images.

4. **Model Training**: Trained the model on both Roboflow and Google Colab environments.

## Results

### Roboflow

- **Data Info**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/c784469c-d43f-475f-9eac-b034fb8e450e)

- **Training Metrics**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/f3d65ab5-4962-48fd-ab1b-456fbdb926bd)
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/46c20548-aad2-4072-896b-892cd3a8cfaa)
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/01f02a20-1760-4c3a-9983-bed7c386bb55)
 

### Google Colab

- **Dataset Download**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/cecbc650-2f58-4fe2-bcce-7a8601f673dc)

- **Model Training**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/67f9a145-e0a9-4b41-86a5-7c0ea6feb8ef)

- **Training Metrics**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/58382abe-2007-4808-a546-fe29e4dc2f3c)

- **Confusion Matrix**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/6a3abf65-98e7-4dd9-b11a-bd6d32625b1e)

- **Model Inference**
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/a8ee52d5-4304-46aa-be0d-3d0e59cad9a8)
 ![image](https://github.com/timothyafolami/Ripe-Raspberry-Object-Detection/assets/109224656/75f1593b-8c63-4b22-958c-b5b71f049015)


These details provide insights into the data and the training process on both Roboflow and Google Colab environments.

Feel free to explore the implementation links and reach out if you have any questions or feedback!
