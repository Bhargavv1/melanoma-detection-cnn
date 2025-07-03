# Melanoma Detection with Deep Learning

This project compares four convolutional neural network (CNN) models for binary classification of dermoscopic skin images. The goal is to detect melanoma vs. other lesions using EfficientNet-B3, ResNet-18, DenseNet-121, and a custom CNN baseline.

## 🧠 Models Used
- Custom CNN (3 conv layers + FC)
- ResNet-18
- DenseNet-121
- EfficientNet-B3

## 🔍 Key Features
- Binary classification using dermoscopic images (mel vs. other)
- Transfer learning with frozen pretrained backbones
- Data augmentation for generalisation
- Performance evaluation using accuracy, precision, recall, F1-score
- Ablation studies and qualitative error analysis

## 🧪 Results (Test Set)
| Model           | Accuracy | Precision | Recall | F1-score |
|----------------|----------|-----------|--------|----------|
| Custom CNN     | 0.73     | 0.77      | 0.76   | 0.76     |
| DenseNet-121   | 0.78     | 0.78      | 0.78   | 0.77     |
| ResNet-18      | 0.80     | 0.81      | 0.80   | 0.80     |
| EfficientNet-B3| **0.95** | **0.95**  | **0.95**| **0.95** |

## 🔒 Dataset Access
The dataset is derived from ISIC 2017–2020 challenge datasets and **cannot be redistributed** due to licensing and ethical constraints. You may access the original data at:  
🔗 https://challenge.isic-archive.com/

## 🧰 Setup
```bash
pip install -r requirements.txt
```
Then open `Final_Deep_learning_assessment_code.ipynb` in Jupyter or Colab.

## 📁 File Structure
- `Final_Deep_learning_assessment_code.ipynb`: Full notebook
- `requirements.txt`: Project dependencies
- `data/`: Empty folder (placeholder for dataset)

## 👤 Author
Bhargav Vaidya – MSc Data Science – Manchester Metropolitan University
