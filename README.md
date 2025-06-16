# Human Activity Recognition using LSTM

This project implements Human Activity Recognition (HAR) using Long Short-Term Memory (LSTM) networks on the UCI HAR dataset.

## Folder Structure
Human-Activity-LSTM/
├── data/ # UCI HAR dataset files
├── notebook/ # Jupyter notebook
│ └── LSTM_HAR.ipynb
├── README.md

## Requirements
- Python 3.6+
- TensorFlow 1.x (or use TensorFlow 2.x with `tf.compat.v1`)
- NumPy
- scikit-learn
- Matplotlib

## How to Run
1. Download the [UCI HAR Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones) and place it inside the `data/` folder.
2. Open `notebook/LSTM_HAR.ipynb` in Jupyter Notebook.
3. Run the notebook step-by-step.

## Results
Achieved test accuracy: ~88.46%
