# Knowledge Distillation for Satellite Image Classification

This project demonstrates knowledge distillation applied to the EuroSAT RGB dataset using TensorFlow and a VGG16-based teacher model. The goal is to transfer knowledge from a large, accurate model (teacher) to a smaller model (student) for efficient inference.

## 🔍 Project Overview

- **Dataset**: EuroSAT RGB (via TensorFlow Datasets)
- **Teacher Model**: Pretrained VGG16 (frozen convolutional base)
- **Student Model**: Custom lightweight CNN
- **Loss**: Combination of categorical crossentropy (hard labels) and MSE (soft labels)
- **Goal**: Improve efficiency and accuracy.

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/hardikmakkar07/knowledge-distillation.git
cd knowledge-distillation
