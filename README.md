# 🤖 Machine Learning Progress Repository

This repository documents my journey of learning and experimenting with **Machine Learning (ML)** concepts, models, and techniques.  
It includes implementations, Jupyter notebooks, and experiments ranging from foundational linear models to deep learning architectures and natural language processing with BERT. More to come!!

---

## 🧩 Overview

This project is a **personal learning collection**, organized into thematic folders.  
Each subfolder contains experiments, notes, and models focused on specific ML topics.

### **Main Sections**

#### 🧮 D2L (Dive into Deep Learning)
This folder includes notebooks inspired by the _Dive into Deep Learning_ textbook, exploring core deep learning concepts such as:

- Linear Regression fundamentals  
- Multi-layer Perceptrons (MLP) and activation functions  
- FashionMNIST image classification using PyTorch  
- Visualization and performance metrics  
- Experiment tracking and saved tensors

#### 🧠 Personal/BERT
Contains experiments in **Natural Language Processing (NLP)**, focusing on:

- Fine-tuning **BERT** on custom text data  
- Simple text classification with `essay.csv` dataset  
- Automation via the `bert_script.sh` helper script  
- Exploration of tokenization and embeddings

---

## 📁 Repository Structure

```
machine-learning-main/
│
├── D2l/
│   ├── Chapter 5/
│   │   ├── MLP(5.2)-1layer.ipynb
│   │   ├── MLP(5.2)-2layers.ipynb
│   │   ├── MNISTFashionPrediction.ipynb
│   │   └── data/FashionMNIST/raw/
│   └── Linear Regression/
│       └── Untitled.ipynb
│
├── Personal/
│   └── Bert/
│       ├── bert.ipynb
│       ├── bert_script.sh
│       └── essay.csv
│
└── README.md
```

---

## 🧠 Concepts Covered

- Linear Regression and optimization  
- Multi-layer Perceptron (MLP)  
- Data preprocessing and normalization  
- Model evaluation and loss analysis  
- Deep learning visualization  
- FashionMNIST dataset handling  
- BERT NLP model fine-tuning  
- Deeper networks to come!

---

## 🧰 Requirements

To set up your environment, install dependencies from the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Alternatively, you can manually install the key libraries used across notebooks:

```bash
pip install torch torchvision torchaudio
pip install numpy matplotlib pandas scikit-learn
pip install transformers datasets tqdm
```

---

## 🚀 How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/machine-learning-main.git
   cd machine-learning-main
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Open Jupyter Notebooks to explore and run experiments:

   ```bash
   jupyter notebook
   ```

4. Navigate to subfolders (e.g., `D2l/Chapter 5/`) and run notebooks interactively.

---

## 📦 Dependencies

See `requirements.txt` for the complete list.  
Main frameworks include:

- PyTorch (`torch`, `torchvision`)
- Transformers (Hugging Face)
- NumPy, Matplotlib, Pandas
- scikit-learn
- tqdm

> “Learning by doing — one model at a time.”
