# Image Classification using BiT
This repository contains an implementation of Image Classification using BiT (Big Transfer) models. BiT is a powerful image classification model that achieves state-of-the-art performance on various visual recognition tasks.

## Table of Contents
- Introduction
- Installation
- Usage
- Dataset
- Model Training
- Model Evaluation
- Results

## Introduction
Image Classification using BiT is an advanced approach for accurately categorizing images into predefined classes. BiT models utilize large-scale pretraining on diverse image datasets, followed by fine-tuning on specific tasks. This repository provides an implementation that allows users to train and evaluate BiT models on their own image classification datasets.

## Installation
To use this repository, follow these steps:

- Clone the repository:
git clone https://github.com/PurnaChandar26/Image-Classification-using-BiT.git
- Install the required dependencies:
pip install -r requirements.txt
## Usage
To train and evaluate the BiT model, follow the instructions provided in the train.py and evaluate.py scripts. Make sure to adjust the configuration parameters according to your specific dataset and requirements.

## Dataset
For training the BiT model, you will need a labeled dataset of images. Ensure that your dataset is organized in a suitable directory structure and the labels are assigned correctly.

## Model Training
To train the BiT model on your dataset, run the train.py script. Adjust the hyperparameters, training configuration, and dataset paths according to your needs. The script will automatically save the trained model checkpoints for future evaluation.

##Model Evaluation
To evaluate the trained BiT model on your dataset, use the evaluate.py script. Update the evaluation configuration and dataset paths accordingly. The script will load the trained model and generate performance metrics such as accuracy, precision, and recall.

## Results
The results obtained from training and evaluating the BiT model will be stored in the results/ directory. This directory contains logs, performance metrics, and visualizations that provide insights into the model's performance.
![3b6ee7bd-cc5b-4022-99b0-7a64572a6a68](https://github.com/PurnaChandar26/Image-Classification-using-BiT/assets/97793147/9788dbe3-f1a9-4882-9450-947d852aefc1)
![d2e0dd2f-2f78-49fa-8f33-61a7ad40c26b](https://github.com/PurnaChandar26/Image-Classification-using-BiT/assets/97793147/b4c37809-5b94-4fc3-a675-506bdb34fb13)
![f3eb63bc-981a-47ef-812a-0b44fb5c4f22](https://github.com/PurnaChandar26/Image-Classification-using-BiT/assets/97793147/5cc5691f-d66b-4fec-a7bd-504a7a979bef)
