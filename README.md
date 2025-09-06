# Image Segmentation Models

This repository contains multiple deep learning models for **semantic segmentation**, trained and evaluated on **Mapillary Vistas** and two additional datasets.  
The goal of this project is to benchmark different segmentation architectures on diverse datasets and analyze their performance.

---

## 📂 Models Implemented

- [AlexNet](./AlexNet.ipynb)  
- [LeNet-5](./LeNet-5.ipynb)  
- [VGG16](./VGG16.ipynb)  
- [MobileNet](./MobileNet.ipynb)  
- [UNet](./unet.ipynb)  
- [Ghost-UNet](./Ghost_unet.ipynb)  
- [Modified Ghost-UNet](./Modified%20Ghost_unet.ipynb)  

Each notebook includes:
- Model architecture  
- Training pipeline  
- Dataset preprocessing  
- Evaluation metrics  
- Visualization of segmentation outputs  

---

## 📊 Datasets

The models are trained and evaluated on the following datasets:

1. **[Mapillary Vistas Dataset](https://www.mapillary.com/dataset/vistas)**  
2. **[CityScapes Dataset](https://www.cityscapes-dataset.com/)**
3. **[CARLA- CAR Learning to Act Dataset](https://carla.org/)**  

---

## 🚀 Training & Evaluation

- Training is implemented in **Tensorflow**.  
- Standard preprocessing (resizing, normalization, augmentation) applied.  
- Models evaluated using:
  - **Pixel Accuracy**  

---
