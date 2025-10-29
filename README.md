# Possum-Classification-Using-CNN-Sequential-vs-Functional-Approach_Deep-Learning

This project aimed to classify possums into Victoria or Other populations based on 13 biological features (e.g., head length, weight, and tail length). A simple CNN-like dense network was implemented using both the Sequential and Functional APIs in Keras to compare performance and architectural flexibility on tabular data.

**Tools**: Python, TensorFlow, Keras, NumPy, Scikit-learn

**Approach**: Developed and compared two models using Keras: a Sequential CNN-based dense network and a Functional model with dual feature paths and concatenation. Both models used Dropout for regularization and ReLU/LeakyReLU activations to capture non-linear relationships in the data.

**Results**: The Sequential model achieved 90% test accuracy, while the Functional model slightly improved performance to 92%. The Functional model showed better recall for “Victoria” but misclassified a few “Other” samples.

**Key Insight**: The Functional approach provided better generalization and flexibility, demonstrating that even simple tabular data can benefit from nonlinear architectural designs beyond a purely sequential setup.
