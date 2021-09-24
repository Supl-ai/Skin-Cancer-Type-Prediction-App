# Skin-Cancer-Type-Prediction-App

Building a model to classify between skin cancer images of type malignant and benign. 
There is upload button where you will be uploading your images and it will classify it with some probability.

# Dataset

The dataset which have been used have been taken from Kaggle.

# Requirements
 
You will need to install fastbook. You can run these commands

pip install fastai fastcore --upgrade
git pull

It will upgrade and install the fastai packages. Nothing more is required.

# GPU

You might wanna use the GPU for training otherwise it will take a lot of time. After training dureing productionizing you may use the cpu.

# Training

We have plenty of images to train and test. The dataset is partitioned in that way. I have trained it for 25 epochs which is showing pretty good results.

# Pickle File

A pickle file has been created so that we don't need to train it many times. If you run this code pickle file will be created and used.

# Productionizing

Voila have been used to productionize and voila is needed to installed for that. Codes are in the ipynb files.
