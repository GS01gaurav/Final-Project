# 🌸 Flower Classification using Deep Learning (PyTorch)

## 📌 Project Overview
This project demonstrates how deep learning can be applied to unstructured image data for multi-class classification. The goal is to classify images of flowers into five categories: daisy, dandelion, rose, sunflower, and tulip.

The model uses transfer learning with a pre-trained ResNet18 architecture to achieve efficient and accurate classification.

## 🧠 Model Architecture
- Pre-trained ResNet18
- Final fully connected layer modified for 5 classes
- Backbone layers frozen (only classification layer trained)
- Loss Function: CrossEntropyLoss
- Optimizer: Adam

## 📂 Dataset
- Daisy: 100 images  
- Dandelion: 100 images  
- Rose: 100 images  
- Sunflower: 100 images  
- Tulip: 100 images  

Total Images: 500

## 🔄 Data Preprocessing
- Image resizing (224 × 224)
- Normalization
- Data augmentation (flip, rotation)

## 🚀 Training Details
- Epochs: 10  
- Training Accuracy: 80.29%  
- Validation Accuracy (Best): 80%

## 📊 Results
Test Accuracy: 72%  
Test Loss: 0.7414  

### Classification Report
- Daisy: Precision 0.60 | Recall 0.80 | F1 0.69  
- Dandelion: Precision 0.70 | Recall 0.47 | F1 0.56  
- Rose: Precision 0.83 | Recall 0.67 | F1 0.74  
- Sunflower: Precision 0.81 | Recall 0.87 | F1 0.84  
- Tulip: Precision 0.71 | Recall 0.80 | F1 0.75  

## 📈 Observations
- Model learned meaningful patterns
- Best class: Sunflower
- Weakest class: Dandelion
- Slight overfitting observed

## ⚠️ Limitations
- Small dataset
- Limited fine-tuning

## 🔧 Future Improvements
- Use more data
- Fine-tune ResNet18
- Try other models (VGG16, EfficientNet)

## 📌 Conclusion
Transfer learning with ResNet18 achieved 72% accuracy on a small dataset, proving its effectiveness for image classification.


