# MNIST Handwritten Digit Classifier

A deep learning project built with **Python, TensorFlow, and Keras** to classify handwritten digits from 0 to 9 using the MNIST dataset.

This project explores how neural network architecture, activation functions, and training configuration affect classification performance.

## Overview

The goal of this project was to build and train a neural network that can recognize handwritten digits from grayscale images.

Starting with a basic model, I experimented with different configurations to improve its performance and evaluated the final model on unseen test data.

### Results

| Metric | Result |
|---|---:|
| Training accuracy | ~99.7% |
| Test accuracy | ~98% |

*Results are approximate and should be updated to match the final recorded evaluation.*

## Technologies Used

- **Python** — programming language
- **TensorFlow** — deep learning framework
- **Keras** — neural network construction and training
- **TensorFlow Datasets (TFDS)** — dataset loading
- **NumPy** — numerical operations
- **Scikit-learn** — confusion matrix and model evaluation
- **Matplotlib** — visualization, if used in the project

## Dataset

The project uses the **MNIST handwritten digit dataset**, which contains 70,000 grayscale images of handwritten digits:

- 60,000 training images
- 10,000 test images
- Image dimensions: 28 × 28 pixels
- Number of classes: 10 (digits 0–9)

Each image is associated with a label representing the digit it contains.

## Model and Experiments

The classifier was developed using TensorFlow/Keras. During experimentation, I explored:

- Different activation functions, including ReLU and Tanh
- Changes to the number of neurons in the hidden layer
- Different numbers of training epochs
- Training, validation, and test performance

These experiments helped me understand how model capacity, activation functions, and training duration can influence performance.

## Evaluation

The model was evaluated using a separate test dataset to measure its performance on previously unseen images.

I also generated a **confusion matrix** to examine individual classification errors and identify which digits the model most frequently confused with one another.

This provides more information than accuracy alone by showing where the classifier performs well and where it struggles.

## Key Learnings

Through this project, I gained practical experience with:

- Building a neural network using Keras
- Understanding the training and validation workflow
- Experimenting with model hyperparameters
- Evaluating classification performance
- Interpreting accuracy, loss, and confusion matrices
- Investigating model errors instead of relying solely on a single metric

## Running the Project

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

### 2. Create and activate a virtual environment

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

### 3. Install dependencies

Once the project dependencies have been documented, install them using:

```bash
pip install -r requirements.txt
```

### 4. Run the project

Open the notebook or Python script included in the repository and run the cells or script in order.

The first run may download the MNIST dataset, depending on the dataset-loading configuration.

## Future Improvements

- Visualize misclassified images alongside their actual and predicted labels
- Investigate the most common digit-confusion patterns
- Compare different neural network architectures
- Track training and validation loss across epochs
- Experiment with regularization and other techniques where useful

## Author

**Aayush Pokhrel**

Computer Science / AI and Software Engineering student interested in Data Science, Machine Learning, and Deep Learning.

---

*Built as part of my hands-on journey into deep learning and machine learning experimentation.*
