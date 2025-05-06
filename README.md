# Clothes_Classification
FashionMNIST with PyTorch
==========================

This project trains and compares 3 models on the FashionMNIST dataset using PyTorch.

Models
------
1. Model V0 – Basic linear model  
2. Model V1 – Linear + ReLU  
3. Model V2 – CNN (like TinyVGG)

Results
-------
Model   | Accuracy | Loss
--------|----------|--------
V0      | 83.43%   | 0.4766
V1      | 75.02%   | 0.6850
V2      | 87.71%   | 0.3348

V2 performs the best.

Requirements
------------
Install dependencies with:

    pip install torch torchvision matplotlib pandas tqdm mlxtend

Sample Output
-------------
After training, the code shows test image predictions.
Green = correct  
Red = wrong

Run It
------
Run this project in Google Colab or a Jupyter Notebook on your computer.
