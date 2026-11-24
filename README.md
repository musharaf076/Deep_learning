# Deep Learning Experiments

This repository contains a collection of practical deep-learning experiments implemented using Python, NumPy, TensorFlow, and Keras. It covers fundamental neural-network concepts, computer vision, recurrent neural networks, transfer learning, explainable AI, and semantic image segmentation.

The experiments are implemented using Jupyter Notebooks and are intended for learning, experimentation, and understanding the practical applications of deep-learning architectures.

## Experiments

| Experiment | Description | Dataset / Application |
|---|---|---|
| **Exp 1 – Perceptron** | Implements a basic perceptron from scratch using NumPy and tests AND, OR, and NOT logic gates. | Logic gates |
| **Exp 2 – Multilayer Perceptron (MLP)** | Builds fully connected neural networks for regression and multiclass classification. Includes feature scaling and hyperparameter tuning. | California Housing, Iris |
| **Exp 3 – Convolutional Neural Network (CNN)** | Implements a CNN for image classification, including convolution, pooling, and dense layers. | CIFAR-10 |
| **Exp 4 – Explainable AI (XAI)** | Explores model interpretability using feature-map visualization and Grad-CAM to understand CNN predictions. | COVID-19 Radiography |
| **Exp 5 – Semantic Image Segmentation** | Implements U-Net and Attention U-Net architectures for pixel-level image segmentation and compares their performance using IoU. | Oxford-IIIT Pet |
| **Exp 6 – Recurrent Neural Networks (RNN)** | Implements and compares SimpleRNN and GRU models for structured time-series forecasting. | Jena Climate |
| **Exp 7 – LSTM Networks** | Applies LSTM and Bidirectional LSTM architectures to structured time-series forecasting and unstructured audio classification. | Jena Climate, Free Spoken Digit |
| **Exp 8 – Transfer Learning and Ensemble Modeling** | Uses pretrained ResNet50 and VGG16 architectures, fine-tunes them for image classification, and combines predictions using ensemble techniques. | CIFAR-10 |

## Technologies and Libraries

The experiments primarily use:

- **Python** – Programming language
- **NumPy** – Numerical computation
- **Pandas** – Data manipulation and preprocessing
- **Matplotlib** – Data visualization
- **Scikit-learn** – Data preprocessing and model evaluation
- **TensorFlow / Keras** – Deep-learning model development
- **Keras Tuner** – Hyperparameter optimization
- **TensorFlow Datasets** – Dataset loading
- **Librosa** – Audio processing and feature extraction

## Installation

Install the required libraries using pip:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras-tuner tensorflow-datasets librosa
```

For running the notebooks locally, install Jupyter:

```bash
pip install notebook
```

## Running the Notebooks

1. Clone or download this repository.
2. Navigate to the repository directory.
3. Install the required dependencies.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the required `.ipynb` file and execute the cells in sequence.

Alternatively, the notebooks can be uploaded and executed using [Google Colab](https://colab.research.google.com/).

## Datasets

The experiments use publicly available datasets, including:

- California Housing Dataset
- Iris Dataset
- CIFAR-10
- COVID-19 Radiography Dataset
- Oxford-IIIT Pet Dataset
- Jena Climate Dataset
- Free Spoken Digit Dataset

Some datasets are downloaded automatically through TensorFlow, Keras, or Scikit-learn. Others may require additional setup depending on the notebook.

## Notes

- These experiments are intended for educational purposes and practical understanding of deep-learning concepts.
- Model performance may vary depending on hardware, software versions, dataset preprocessing, and training parameters.
- A GPU-enabled environment, such as Google Colab, is recommended for computationally intensive experiments.
- Execute notebook cells in order to avoid dependency and variable-reference issues.

## Author

Developed as part of academic deep-learning practical experiments, with a focus on understanding neural-network architectures and their real-world applications.