This repository contains a hands-on Deep Learning practice notebook designed to strengthen foundational knowledge in neural networks, model training workflows, and image preprocessing. The notebook walks through loading datasets, preparing data, building models using TensorFlow/Keras, training, evaluating performance, and visualizing results.

📘 Overview

The notebook (Dl2.ipynb) demonstrates core deep learning concepts using simple, clean examples.
It includes:

Data loading using torchvision utilities

Image preprocessing & normalization

Neural network creation with Keras

Training and evaluation on image datasets

Metric visualization (loss & accuracy)

Saving/loading models and objects

This notebook serves as an exercise to practice DL concepts through experimentation.

🔧 Technologies Used

Python

TensorFlow / Keras

Torchvision

NumPy & Pandas

Matplotlib

Pickle (for basic object serialization)

📦 Dataset

The notebook uses sample image datasets from torchvision.datasets (CIFAR-style datasets) and demonstrates:

Downloading datasets

Applying transforms

Normalization

Preparing data for training/testing splits

🏗 What the Notebook Covers
✔️ Data Preprocessing

Loading image datasets

Resizing & reshaping

Normalization

Applying torchvision.transforms

Preparing train/test splits

✔️ Deep Learning Models

Building neural networks using Keras Sequential API

Dense layers and activation functions

Softmax-based classification

Configuring loss functions & optimizers

✔️ Training & Evaluation

model.fit() for training

model.evaluate() for accuracy

Training history visualization

Plotting accuracy and loss curves

✔️ Visualizations

Displaying sample images

Training/validation performance graphs

✔️ Saving Experiments

Saving models

Saving results or objects using pickle

📈 Results

The notebook demonstrates:

End-to-end workflow from dataset → preprocessing → model → training → evaluation

Visual performance analysis

Examples of prediction and basic evaluation
