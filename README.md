# 🎨 Artist Classification using Deep Learning

A deep learning project built with **PyTorch** for classifying artworks by their artists using a custom Convolutional Neural Network (CNN).  
The model learns artistic styles, color distributions, textures, and brushstroke patterns directly from images.

---

## 📌 Overview

This project was developed for the **Artworks Artist Classification** Kaggle competition.  
It implements a full deep learning pipeline including:

- Custom dataset handling
- Image preprocessing
- CNN architecture design
- GPU training with CUDA
- Prediction generation
- Kaggle submission creation

The model was trained on thousands of artwork images and predicts the corresponding artist for unseen paintings.

---

## 🧠 Model Architecture

The project uses a custom CNN.

### Feature Extraction
Each convolution block contains:
- `Conv2D`
- `BatchNorm2D`
- `ReLU`
- `MaxPooling`

### Classification Head
- Adaptive Average Pooling
- Fully Connected Layers
- Dropout Regularization
- Multi-class Output Layer

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- Pandas
- PIL (Python Imaging Library)
- CUDA / GPU Acceleration
- Kaggle Notebooks

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/artist-classification-cnn.git
cd artist-classification-cnn
```

Install dependencies:

```bash
pip install torch torchvision pandas pillow
```

---

## ▶️ Run the Project

Run the training script:

```bash
python train.py
```

Or open the notebook in Kaggle/Jupyter Notebook.

---

## 🔮 Future Improvements

- Data augmentation
- Transfer learning with ResNet/EfficientNet
- Validation accuracy tracking
- Early stopping
- Learning rate schedulers
- Confusion matrix visualization
- Hyperparameter tuning

---

## 📚 What I Learned

This project helped me strengthen my understanding of:

- Convolutional Neural Networks (CNNs)
- Image classification pipelines
- PyTorch datasets and dataloaders
- GPU-accelerated deep learning
- Multi-class classification
- Kaggle competition workflows

