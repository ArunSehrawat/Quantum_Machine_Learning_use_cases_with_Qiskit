# Quantum Machine Learning (QML) use cases with [Qiskit](https://qiskit.org/)

__(1) Fraud_Detection_with_Qiskit:__ In the notebook, we have taken [credit card fraud detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)---a crucial use case in the financial industry---from the Kaggle competition.
The data is made of 284807 normal as well as fraudulent credit card transactions. Here the task is to train a machine-learning model that can classify normal and fraudulent transactions. In the notebook, we have given an implementation of the [Variational Quantum Classifier __(VQC)__](https://qiskit.org/documentation/stable/0.19/stubs/qiskit.aqua.algorithms.VQC.html#qiskit.aqua.algorithms.VQC), which is a part of the QML module of Qiskit.

__(2) Feature_Selection_with_Qiskit:__ In this notebook, we have taken [sklearn.datasets](https://scikit-learn.org/stable/datasets/toy_dataset.html) and shown how to cast __feature selection__ as a Quadratic Unconstrained Binary Optimization (__QUBO__) problem [[arXiv:2104.04049](https://arxiv.org/abs/2104.04049), [arXiv:2203.13261](https://arxiv.org/abs/2203.13261)] and then solved it with [Qiskit Optimization](https://qiskit.org/ecosystem/optimization/). 
After Feature selection, we have shown how to perform classification with [Qiskit Machine Learning](https://qiskit.org/ecosystem/machine-learning/)

__(3) QUBO_with_Qiskit:__ In this notebook, we have shown how to generate a general __QUBO__ problem and solve it using [__VQE__](https://qiskit.org/documentation/stubs/qiskit.algorithms.minimum_eigensolvers.SamplingVQE.html) and [__QAOA__](https://qiskit.org/documentation/stubs/qiskit.algorithms.QAOA.html) implementation of Qiskit. We have also given other methods for solving a QUBO problem.

<img src="https://github.com/ArunSehrawat/Quantum_Machine_Learning_use_cases_with_Qiskit/assets/99533657/658d7316-ff38-4a2b-ae08-573c4860516e" width=40% height=40%>


__(4) Image_Classification_using_QNN_with_Qiskit:__ In this notebook, we have created a dataset of images. Each image is---a binary matrix---made of either vertical strips (class 1) or horizontal strips (class 0). Here the machine learning task is to classify these two kinds of images. The task is completed using the [__VQC__](https://qiskit.org/documentation/stable/0.19/stubs/qiskit.aqua.algorithms.VQC.html#qiskit.aqua.algorithms.VQC).


<img src="https://github.com/ArunSehrawat/Quantum_Machine_Learning_use_cases_with_Qiskit/assets/99533657/6a5a76ae-58d5-426a-85d6-3b09360adf7a" width=40% height=40%>


