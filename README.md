# AI Foundations: Computer Vision & Text Sentiment Models

A hands-on repository showcasing foundational Deep Learning and Natural Language Processing (NLP) models built from scratch in Python using cloud GPU acceleration.

## 🚀 Projects Overview

### 1. Computer Vision Digit Classifier
A deep learning neural network trained to recognize and classify handwritten numbers (0-9).
* **Dataset:** MNIST (70,000 handwritten digit images).
* **Framework:** PyTorch (`torch.nn`).
* **Architecture:** Fully Connected Neural Network utilizing Flatten layers, dense Hidden layers, and ReLU activation functions.
* **Performance:** Achieved **96.19% test accuracy** in just 3 training epochs.

### 2. NLP Sentiment Analyzer
A text classification AI that processes natural language strings to determine whether the underlying emotional tone is positive or negative.
* **Framework:** Scikit-Learn.
* **Methodology:** TF-IDF Vectorization combined with a Logistic Regression classifier.
* **Capability:** Converts raw text tokens into mathematical word-frequency matrices to output live classification confidence levels.

## 🛠️ Tech Stack & Skills
* **Languages:** Python
* **Libraries:** PyTorch, Scikit-Learn, NumPy, Matplotlib
* **Environment:** Google Colab (T4 GPU Accelerated Runtime)

## 🧠 Engineering Concepts Demonstrated
* **Backpropagation:** Manually managing gradient descents using `loss.backward()` and the Adam optimizer to systematically minimize training loss.
* **Data Flattening:** Transforming 2D spatial pixel matrices ($28 \times 28$) into 1D vectors for neural network ingestion.
* **Text Embedding:** Vectorizing text data to map word weightage based on contextual frequency.
