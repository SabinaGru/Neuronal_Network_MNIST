# Neuronal_Network_MNIST
NN with MNIST dataset from scratch

<div style="display: flex; gap: 20px;">
  <img src="https://github.com/user-attachments/assets/1a2e8481-9155-44a6-8285-68ed5ea82a63" alt="image" width="300"/>
  <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*3VNBdeax5uKmbAJuXLShCw.png" alt="image" width="345"/>
</div>



## Summary
In this notebook, neural networks were designed and trained to correctly classify the MNIST dataset of handwritten digits. After examining the details of the dataset, a linear layer was implemented as the foundational building block of neural networks. A simple model was then created with one hidden layer and an output layer to identify images containing the digit "4."

During this process, a challenge was encountered due to the fact that only one out of ten images contains a "4." This class imbalance caused the model to learn to never predict a "4." The issue was addressed by applying class weighting or oversampling techniques.

Next, a deeper network with three hidden layers was constructed to classify all digits correctly. An issue arose when training on the entire dataset at once, causing the model to stagnate or degenerate. By dividing the training process into smaller batches, this problem was successfully resolved.

In conclusion, this notebook demonstrates that neural networks can be applied to solve various complex tasks with the same basic structure. However, the optimization required can vary significantly depending on the specific problem. The primary aim of this work was to practice mathematical thinking and communication in practical applications, rather than achieving optimal results. As such, the models presented here are far from reaching an optimal outcome.


<img src="https://github.com/user-attachments/assets/7892a72c-3896-41e9-9dc4-7e468805157d" alt="image" width="300"/>



---
## Steps taken:
* explore MNIST dataset
* create a class for the layers of a neural network
* create a neural network with a hidden layer to identify fours
* train network with different hyperparameters
* create and train a deep neural network with 3 hidden layers to classify handwritten digits
---

### Used packages:
* torchvision only for import dataset!
* matplotlib
* numpy
