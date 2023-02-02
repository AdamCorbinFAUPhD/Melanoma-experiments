# Melanoma-experiments

This repo is a collection of experiments that evaluate fairness in machine learning for dermatology. 

We evaluate the following models:
1. EfficientNet - b2
1. ResNet50

Here are the datasets used:


1. [cdeotte/jpeg-melanoma-256x256](https://www.kaggle.com/datasets/cdeotte/jpeg-melanoma-256x256) - Triple stratified dataset between sex, age, and skin condition. This was the base for the next datasource
1. [nroman/melanoma-external-malignant-256](https://www.kaggle.com/datasets/nroman/melanoma-external-malignant-256) - Source data used for training
1. [andradaolteanu/siim-melanoma-prep-data](https://www.kaggle.com/datasets/andradaolteanu/siim-melanoma-prep-data) - Cleaned metadata, added missing values, and encoded data
1. Test dataset - [ISIC 2016 task 3](https://challenge.isic-archive.com/landing/2016/39/) skin leasion classificaiton
