# Building a Neural Network From Scratch

Why waste time reinventing the wheel?

After spending months in the classroom, learning the statistical computation behind artificial neurons, layers, losses, gradients, and backpropagation, it almost felt like I was cheating when I provided inputs to a package and magically arrived at the results. 

I started writing simple non-linear equations like sigmoid and softmax. Eventually got to defining loss function and updating weights through backpropagation. Honestly, the code is not great with time complexity O(epochs*input_size). But, it does the job of classification with good accuracy.

Implementation:
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
