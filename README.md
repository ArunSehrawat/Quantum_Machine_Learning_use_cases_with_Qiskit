# Quantum Machine Learning (QML) use cases with [Qiskit](https://qiskit.org/)

__(1) Fraud_Detection_with_Qiskit:__ In the notebook, we have take [credit card fraud detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)---a crucial use case in the financial industry---from the kaggle competition.
The data is made of 284807 normal as well as fraudulent credit card transactions. Here the task is to train a machine learning model that can classify normal and fraud transactions. In the notebook, we have given an implementation of [Variational Quantum Classifier (VQC)](https://qiskit.org/documentation/stable/0.19/stubs/qiskit.aqua.algorithms.VQC.html#qiskit.aqua.algorithms.VQC), which is a part of the QML module of Qiskit.

__(2) Feature_Selection_with_Qiskit:__ In this notebook, we have taken [sklearn.datasets](https://scikit-learn.org/stable/datasets/toy_dataset.html) and shown how to cast __feature selection__ as a Quadratic Unconstrained Binary Optimization (__QUBO__) problem [[arXiv:2104.04049](https://arxiv.org/abs/2104.04049), [arXiv:2203.13261](https://arxiv.org/abs/2203.13261)] and then solved it with [Qiskit Optimization](https://qiskit.org/ecosystem/optimization/). 
After Feature selection, we have shown how to perform classification with [Qiskit Machine Learning](https://qiskit.org/ecosystem/machine-learning/)

__(3) QUBO_with_Qiskit:__
