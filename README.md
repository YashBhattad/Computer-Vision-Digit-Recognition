# Computer Vision – Digit Recognition with Deep Learning

This repository showcases two deep learning projects using **TensorFlow/Keras** to recognize handwritten digits (0–9) from the **MNIST dataset**.  
It demonstrates both a **basic neural network** and a **CNN (Convolutional Neural Network)**, highlighting the progression from simple models to more powerful computer vision architectures.

## 📌 Projects Included
1. **MNIST_Basic_NN.ipynb**  
   - Implements a simple feedforward neural network  
   - Demonstrates the core workflow: load → train → evaluate  

2. **MNIST_CNN_From_Scratch.ipynb**  
   - Builds a CNN from scratch with Conv2D, MaxPooling, Dense, Dropout  
   - Achieves higher accuracy and robustness compared to the basic NN  

## ⚙️ Requirements
- Python 3.8+  
- TensorFlow 2.x  
- NumPy, Matplotlib, scikit-learn  

Install dependencies:
```bash
pip install tensorflow numpy matplotlib scikit-learn
```

## ▶️ How to Run

Clone this repository:

```bash
git clone https://github.com/your-username/computer-vision-digit-recognition.git
cd computer-vision-digit-recognition
```

Open either notebook in Jupyter Notebook or VS Code.

Run cells sequentially to train and evaluate the models.

---

## 📊 Results

- **Basic NN:** Learns to classify digits with decent accuracy
- **CNN:** Significantly outperforms NN with higher test accuracy

---