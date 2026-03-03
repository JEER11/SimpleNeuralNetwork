# SimpleNeuralNetwork
small applied-ML notebook that implements and compares basic losses, builds a 2-layer NumPy neural network, trains/evaluates it on a synthetic binary classification dataset, and visualizes loss surfaces, decision boundaries and hyperparameter effects.

---
# Part 1: Loss Functions Implementation and Analysis
Implement various loss functions and understand their mathematical properties and use cases.
### Task 1.1: Visualize Loss Function Behavior
<img width="1216" height="590" alt="image" src="https://github.com/user-attachments/assets/58a9550c-d34e-4e7a-95cd-d7d81bdd743f" />

---
# Part 2: Neural Network from Scratch
A simple neural network using only NumPy, using forward propagation, backward propagation, and gradient descent.

### Task 2.1: Create Dataset and Test Neural Network
Training data shape: (800, 2)
Training labels shape: (800, 1)
Test data shape: (200, 2)
Test labels shape: (200, 1)
<Figure size 1000x400 with 2 Axes><img width="990" height="390" alt="image" src="https://github.com/user-attachments/assets/76b0baff-d926-4cc0-8d92-5d1c595d0995" />

### Task 2.2: Train and Evaluate the Neural Network
Training Neural Network...
========================================
Epoch 0/1000, Loss: 0.3569, Accuracy: 0.4963
Epoch 100/1000, Loss: 0.1468, Accuracy: 0.8850
Epoch 200/1000, Loss: 0.1019, Accuracy: 0.9113
Epoch 300/1000, Loss: 0.0847, Accuracy: 0.9300
Epoch 400/1000, Loss: 0.0767, Accuracy: 0.9287
Epoch 500/1000, Loss: 0.0723, Accuracy: 0.9225
Epoch 600/1000, Loss: 0.0694, Accuracy: 0.9237
Epoch 700/1000, Loss: 0.0672, Accuracy: 0.9263
Epoch 800/1000, Loss: 0.0655, Accuracy: 0.9287
Epoch 900/1000, Loss: 0.0641, Accuracy: 0.9300

Final Results:
Training Accuracy: 0.9300
Test Accuracy: 0.9150

### Task 2.3: Visualize Training Progress and Decision Boundary
<Figure size 1500x1000 with 7 Axes><img width="1489" height="990" alt="image" src="https://github.com/user-attachments/assets/cd3afcb5-17e4-42f5-9b65-08c084167713" />


---
# Part 3: Hyperparameter Exploration
Experiment with different hyperparameters to understand their impact on training.
<Figure size 1500x1000 with 4 Axes><img width="1489" height="990" alt="image" src="https://github.com/user-attachments/assets/4b161d0c-523a-4851-b029-2bea97ce3dda" />

Hyperparameter Experiment Summary:
========================================
Learning Rate Results:
  LR=0.001: Final Test Acc=0.3200, LossHistoryLen=500
  LR=0.01: Final Test Acc=0.6050, LossHistoryLen=500
  LR=0.1: Final Test Acc=0.8600, LossHistoryLen=500
  LR=1.0: Final Test Acc=0.9150, LossHistoryLen=500

Hidden Layer Results:
  Hidden=3: Test Acc=0.8650
  Hidden=5: Test Acc=0.8600
  Hidden=10: Test Acc=0.8950
  Hidden=20: Test Acc=0.9050
  Hidden=40: Test Acc=0.9100
  Hidden=80: Test Acc=0.9150

  





































