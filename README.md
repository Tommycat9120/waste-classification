# AI-Powered Waste Classification ♻️

## Overview
This project implements an **AI-driven waste classification model** to automate the sorting of organic and recyclable waste. Using a deep learning approach, we aim to enhance efficiency in waste management systems, reducing landfill dependency and promoting sustainability.

## Features 🚀
- **Deep Learning-Based Model**: Utilizes a fine-tuned **VGG16** architecture for waste classification.
- **High Accuracy**: Achieves **92% accuracy**, outperforming benchmark models.
- **Robust Dataset**: Trained on **22,500 labeled images** from **Mendeley** and **Kaggle** datasets.
- **Scalable Deployment**: Designed for integration with **smart bins, IoT systems, and waste management infrastructure**.
- **Sustainability Impact**: Reduces pollution, labor costs, and improves recycling efficiency.

## Dataset 📊
We used the following dataset for training:
- **Kaggle Waste Classification data**: https://www.kaggle.com/datasets/techsash/waste-classification-data 

## Model Architecture 🧠
- **Base Model**: Pre-trained **VGG16** on ImageNet.
- **Modifications**: Final layers replaced for **binary classification** (organic vs. recyclable).
- **Optimization**: Freezing early layers, training only the final classification layer.
- **Alternatives Considered**: ResNet50 (higher accuracy, computationally expensive), MobileNetV2 (efficient but lower accuracy).

## Implementation 🛠️
1. **Data Preprocessing**
   - Resize images to **224x224 pixels**.
   - Normalize pixel values.
   - Apply **data augmentation** (rotation, flipping, brightness adjustments).
2. **Model Training**
   - Split dataset into **training (80%)**, **validation (20%)**, and **testing (15%)**.
   - Train the model using **cross-entropy loss and Adam optimizer**.
   - Evaluate using **accuracy, precision, recall, and F1-score**.
3. **Results**
   - Outperforms **LeNet benchmark (0.89 accuracy) with 0.92 accuracy**.

## Deployment 🔧
Possible deployment strategies:
- **Smart Bins**: AI-powered waste sorting in public and private spaces.
- **Cloud-Based AI**: Real-time classification through IoT-enabled devices.
- **Recycling Plants**: Integration with **conveyor belts** and **robotic arms** for automated sorting.

## Challenges & Future Improvements 🚧
- **Handling Mixed Waste**: Enhancing model robustness for images containing multiple waste types.
- **Scalability**: Ensuring real-time performance on edge devices.
- **Ethical Considerations**: Addressing data privacy concerns for public waste collection.
- **Model Compression**: Exploring **lightweight models** for mobile and embedded deployment.

## Contributors 👥
- **Alex Calfee** 
- **Ananya Awasthi** 
- **Tanya Singh** 
- **Tom Xie** 
- **Yaxuan Qi** 

## Contact 📬
For questions or collaborations, feel free to reach out to any of the contributors or open an issue on GitHub!

---
💡 *Help us revolutionize waste management with AI!* 🚀🌱
