# Handwritten Character Recognition with CNN (PyTorch + Colab)

This project is a beginner-friendly deep learning experiment to train a **Convolutional Neural Network (CNN)** on **my own handwritten letters** using PyTorch and Google Colab.

The goal is to understand the full machine learning pipeline — from dataset creation to training, testing, and interpreting model predictions.

---

## What I Did

- Created a small dataset of my handwritten **'A'** characters
- Used `ImageFolder` to automatically label data by folder structure
- Applied transforms (grayscale, resizing, normalization)
- Built a simple CNN with PyTorch using `Conv2d`, `ReLU`, `MaxPool`, and `Linear` layers
- Trained the model and observed decreasing loss
- Tested predictions and interpreted model confidence
- Learned about **epochs, layers, tensors, ReLU, loss functions, and model outputs**

---

## Why This Matters

I wanted to:
- Learn how neural networks actually work — not just use them
- Understand what tools like PyTorch and Colab are doing under the hood
- Practice building a working system from scratch using AI as a learning partner
- Build confidence in machine learning by doing something *real* and *tangible*

---

## Tools & Libraries

- **Google Colab** – for training in the cloud
- **PyTorch** – to define and train the CNN
- **Torchvision** – to load and preprocess image data
- **Matplotlib** – for visualizing predictions
- **OS / PIL** – for file access and image handling

---

##  Current Limitations

- Only one class trained: `'A'`
- Small dataset (~few samples)
- Basic CNN (tiny architecture, only 2 conv layers)
- Tested on training data only (no validation set yet)

---

## What I Learned

- How CNNs process images using convolution, pooling, and fully connected layers
- What tensors are and how they flow through a model
- What model "confidence" means in binary classification
- How to structure image datasets using folder names as labels
- That I don't need to understand every line of code on day one to still *build and learn something meaningful*

---

## Next Steps (See TODO Below)

- Add more classes (B, C, numbers, etc.)
- Improve accuracy with more training and epochs
- Save and reload the model
- Visualize training results
- Possibly deploy with Flask

---

## How to Run

1. Clone the repo or open in [Google Colab](https://colab.research.google.com)
2. Upload your own dataset of handwritten characters (zip format)
3. Run the notebook step by step

---

## Author

Made with ✨ curiosity and confusion by Marcy.
