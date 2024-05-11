# Deep Learning Models of Various Datasets

1. **MNIST**
2. **CIFAR-10**
3. **Animals-10** ([Kaggle Animals-10](https://www.kaggle.com/datasets/alessiocorrado99/animals10))
4. **Sentiment Analysis of Drug Reviews** ([UCI Repo Drug Reviews](https://archive.ics.uci.edu/dataset/462/drug+review+dataset+drugs+com)) 
5. **Protein Benchmarks** ([Kaggle Protein Stability](https://www.kaggle.com/datasets/djokester/protein-benchmarks?select=stability.train.csv))

## MNIST_Analysis
- Trained on:
    - Deep Neural Network (DNN) with different learning rates

## BN_Exp_with_CIFAR10
- Trained on:
    - DNN with He initialization, Exponential Learning Rate, and Exponential Linear Unit (ELU)
    - DNN with Batch Normalization and ELU

## Transfer_Learning_InceptionV3
- Transfer Learning of Inception V3 with two extra dense layers

## Drug_Reviews
- Trained on:
    - Gated Recurrent Unit (GRU) Model with Dense Layers and Dropout
    - Simple GRU Model
    - Simple Long Short-Term Memory (LSTM) Model with Different Batch Sizes
    - LSTM Model with Dense Layers and Dropout

## Protein_Stability_Project
- Trained models:
    - Linear Regression, Decision Tree, and Random Forest
    - Two DNN Models: One with regularization (Batch Normalization and Dropout) and the other without
    - Two LSTM Models: One with regularization (Dropout) and the other without
    - Two GRU Models: One with regularization (Dropout) and the other without
    - Two 1D Convolution Neural Network (CNN) Models: One with regularization (Dropout) and the other without
    - Combination of a 1D CNN and GRU Model
- Written Report of the Results
