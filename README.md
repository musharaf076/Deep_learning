# Deep Learning Experiments

This repository contains three Jupyter notebooks covering introductory neural-network concepts and practical deep-learning models.

## Contents

| Notebook | Description |
|---|---|
| `Exp 1.ipynb` | Implements a basic perceptron from scratch using NumPy and tests it on AND, OR, and NOT logic gates. |
| `Exp2.ipynb` | Builds and evaluates fully connected neural networks for two tasks: California Housing regression and Iris multiclass classification. It uses TensorFlow/Keras, feature scaling, and Keras Tuner. |
| `Exp3.ipynb` | Builds a convolutional neural network (CNN) with TensorFlow/Keras for image classification using the CIFAR-10 dataset. The notebook uses a subset of the dataset and normalizes image pixel values. |

## Requirements

The notebooks use Python and the following main libraries:

- NumPy
- pandas
- Matplotlib
- scikit-learn
- TensorFlow
- Keras Tuner (`keras-tuner`)

Install the packages with:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras-tuner
```

If you are running the notebooks in Jupyter, you may also need:

```bash
pip install notebook
```

## Running the notebooks

1. Clone or download this repository.
2. Open a terminal in the repository folder.
3. Install the dependencies listed above.
4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook you want to run and execute its cells in order.

**Dataset note:** `Exp2.ipynb` fetches the California Housing dataset through scikit-learn, which requires an internet connection the first time it is downloaded. `Exp3.ipynb` loads CIFAR-10 through Keras, which may also require an internet connection for the initial download.

## Notes

- These notebooks are intended for learning and experimentation.
- Model results can vary depending on the software versions, hardware, and training settings.
- Run the cells from top to bottom. Some notebooks install or download dependencies/data during execution.
