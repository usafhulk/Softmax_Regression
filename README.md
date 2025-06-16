# Softmax Regression Portfolio Project

Welcome to my Softmax Regression project! I built this repository to demonstrate my understanding of both the theory and practical implementation of Softmax Regression—a core algorithm for multi-class classification in machine learning. My focus was to create clear, well-documented code and notebooks that not only work, but also teach.

## 🚩 Project Overview

This repo contains several Jupyter notebooks where I:

- Implement Softmax Regression from scratch using PyTorch.
- Visualize model weights, data, and training progress.
- Use both synthetic and real-world datasets (MNIST).
- Explore, train, and evaluate models with detailed output and analysis.

It serves as a hands-on showcase of my machine learning abilities, Python skills, and my approach to explainability and reproducibility.

## 📁 Repository Contents

- **Softmax Classifier.ipynb**  
  My walk-through of building a Softmax regression model for MNIST digit recognition. Includes visualization of model parameters, loss, and accuracy curves, plus misclassification analysis.
- **Softmax.ipynb**  
  A step-by-step, highly annotated deep dive into Softmax Regression for MNIST, covering data loading, preprocessing, architecture, training loop, and result analysis.
- **Softmax Classifier 1D.ipynb**  
  Implementation of Softmax Regression on a simple, synthetic 1D dataset for three-class classification. Designed to clearly illustrate the mechanics of the algorithm and decision boundaries.
- **data/**  
  Contains the MNIST dataset (downloaded automatically by the notebooks if not present).
- **.gitignore**  
  Standard Python and notebook ignores to keep the repo clean.

## 🛠️ How to Run

1. **Clone this repo:**
   ```bash
   git clone https://github.com/usafhulk/Softmax_Regression.git
   cd Softmax_Regression
Install dependencies:
I recommend creating a virtual environment first.
bash
pip install torch torchvision matplotlib numpy
Open a notebook:
Launch Jupyter and open any of the .ipynb files.
bash
jupyter notebook
For MNIST experiments, use Softmax Classifier.ipynb or Softmax.ipynb.
For a didactic, line-by-line intro, try Softmax Classifier 1D.ipynb.
The MNIST data will be downloaded automatically if missing.

#### 🌟 Why This Project?
I created this project to:

Deepen my understanding of Softmax Regression by building it from scratch.
Practice clean, readable, and well-commented code.
Visualize what the model “learns” and how it makes decisions.
Show my ability to work with both toy and real datasets.
Provide an educational resource for others getting started with multi-class classification. <br/>
<br/>

#### 📊 Example Results
Achieved ~90% validation accuracy on MNIST with a single-layer Softmax classifier.
Visualized model weight matrices as images to interpret what the model “sees” for each digit.
Illustrated clear separation and decision boundaries on synthetic data.<br/>
<br/>

#### 🤖 Libraries Used
PyTorch (torch, torch.nn, torch.utils.data)
torchvision (for MNIST dataset)
matplotlib, numpy<br/>
<br/>

#### 🧑‍💻 About Me
My name is Chris. I'm passionate about machine learning, deep learning, and making complex ideas accessible. My goal with this repo is not just to “get results,” but to demonstrate and teach the underlying process.

If you have feedback, ideas, or questions, feel free to reach out or open an issue!

Thank you for checking out my portfolio piece. If you found it useful or interesting, let me know!

Code
Let me know if you want to tweak or add anything!
