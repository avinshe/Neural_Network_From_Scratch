# Building a Neural Network From Scratch

Why waste time reinventing the wheel?

To put myself in the shoes of the inventor and feel his/her/their pain. How can I expect myself to improve/work on a product if I cannot create it in the first place?

After spending months in the classroom learning the statistical computation behind artificial neurons, layers, losses, and backpropagation, it almost feels like I am cheating when I provide inputs to a package and have it spit out the results. I started writing simple non-linear equations like sigmoid and softmax. Eventually got to defining loss function and updating weights through backpropagation.

Honestly, the code is not great with time complexity O(epochs*input_size). But, it does the job of classification with good accuracy. Perhaps, if I spent more time with literature review, I would be able to optimize the code. Who knows? Maybe I can build a whole new AI megacity if I spend enough time. No, I’m not crazy. I took an online assessment that said I’m very normal :)

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

### NOTE: Parts of code are referenced from online. I guess I did not technically start from scratch. Don't come at me bruh! I'm confessing before you find out.
