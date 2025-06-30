# Cat-vs-Dog-Image-Classification-CNN-Architectures-Transfer-Learning




# 🐱🐶 Cat vs Dog Image Classification

This project explores the effectiveness of Convolutional Neural Network (CNN) architectures and Transfer Learning for binary image classification: distinguishing between cats and dogs.

## 🧪 Models Trained

1. ✅ **Shallow-Narrow CNN** — 2 Conv layers, few filters
2. ✅ **Shallow-Wide CNN** — 2 Conv layers, many filters
3. ✅ **Deep-Narrow CNN** — 4 Conv layers, few filters
4. ✅ **Deep-Wide CNN** — 4 Conv layers, many filters
5. ✅ **Transfer Learning** using MobileNetV2 (`imagenet` weights)

All models are trained using the same dataset and evaluated on validation accuracy and loss.

## 📊 Results Summary

| Model             | Final Validation Accuracy | Observations          |
|------------------|---------------------------|------------------------|
| Shallow-Narrow    | ~68%                      | High overfitting       |
| Shallow-Wide      | ~61%                      | Fast training, overfitting |
| Deep-Narrow       | ~72%                      | Balanced & stable      |
| Deep-Wide         | ~66%                      | Fluctuating, unstable  |
| Transfer Learning | **~96%**                  | 🔥 Best performance    |

## 📁 Dataset

Dataset used: [Dog and Cat Classification Dataset on Kaggle](https://www.kaggle.com/datasets/bhavikjikadara/dog-and-cat-classification-dataset)
