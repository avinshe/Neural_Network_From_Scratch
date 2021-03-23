# Building a Neural Network From Scratch

Why waste time reinventing the wheel?

To put myself in the shoes of the inventor and feel his/her pain. 

After spending months in classroom learning the statistical computation behind artificial neurons, layers, losses, and back propagation, it almost feels like I am cheating when I provide inputs to a package it spits out the results. I started writing simple non-linear equations like sigmoid and softmax. Eventually got to defining loss function and updating weights through back propagation.

The code sucks with time complexity O(epochs*input_size). But it does the job and classifies with good accuracy. Perhaps, if I spent more time with literature review, I would be able to optimize the code. Who knows? Maybe I can build a whole new AI megacity if I spend enough time. No, I’m not crazy. I took an online assessment that said I’m very normal :)

### NOTE: Few parts of code is referenced from online. I guess I did not start from scratch. Don't come at me bruh!

Implementations:
1. Hidden Layer
    - Sigmoid Activation
    - Sigmoid Gradient
2. Output Layer
    - Softmax Activation
    - Softmax Gradient
3. Loss
    - Categorical CrossEntropy Loss
    - CrossEntropy Gradient
4. ModelBuild
    - Forward pass
    - Backward pass
    - Model Evaluation
5. Plots
    - Loss vs Epochs
    - Accuracy vs Epochs
6. Testing
    - UCI ML Database - Flag data Training Accuracy 96%, Validation Accuracy 94%
    - UCI ML Database - Iris data Training Accuracy 97%,Validation Accuracy 97%
