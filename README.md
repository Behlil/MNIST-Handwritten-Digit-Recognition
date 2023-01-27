# MNIST Handwritten Digit Recognition

This repository contains the code for a machine learning model trained to recognize handwritten digits from the MNIST dataset. The goal of this project is to correctly identify digits from a dataset of tens of thousands of handwritten images, and to experiment with different machine learning techniques to improve the model's performance.

## Dependencies
- Python 3
- Tensorflow
- Numpy
- Matplotlib
- Sklearn

## Downloading the Data
1. Go to the following link: `https://www.kaggle.com/competitions/digit-recognizer/data`

2. Log in to your Kaggle account.

3. Scroll down to the "Data" section and click on the "Download All" button to download a zip file containing the train.csv and test.csv files.

4. Extract the downloaded zip file, the train.csv and test.csv files should be in the extracted folder.
## Usage
1. Clone the repository: \
`git clone https://github.com/Behlil/Digit-Recognizer`
2. Install the dependencies: \
`pip install -r requirements.txt`
3. Run the jupyter notebook: \
`jupyter notebook mnist-handwritten-digit-recognition.ipynb`
4. Follow the instructions in the notebook to train and test the model

## Results

The model achieved an accuracy of 98% on the test set.

## Acknowledgements

- The MNIST dataset is a classic dataset in the field of computer vision and serves as a benchmark for classification algorithms.
- The tutorial-style kernels provided by the competition organizers were used as a guide for our experimentation and learning process.

## Note

This project is just a prototype and is not meant to be used in any production environment. The model is not well optimized and can be improved by using more advanced techniques and architectures.
