Attention is all you need is the step by step implementation

and Final GPT is the end product

What is the project:\n

a GPT-like model, starting from a basic bigram language model and progressively incorporating advanced attention techniques. My goal is to observe and document the improvements in performance as I enhance my model with more and more attention mechanishms step by step.

Models made:
1. Bigram Language model
2. Added self attention
3. Added multihead attention
4. Added layer normalization
5. Added projection and feed forward layers to add complexity to the model

The loss(cross entropy) is observed to be reducing with each added mechanism
| **Models Made**                                   | **Loss(Cross Entropy)** |
|---------------------------------------------------|------------|
| 1. Bigram Language Model                          | 2.48       |
| 2. Added Self-Attention                           | 2.37       |
| 3. Added Multi-Head Attention                     | 2.17       |
| 4. Added Feed forward Layer                       | 2.22       |
| 5. Multiple multi head attention blocks           | 1.96       |

###Final Loss when trained for more epochs: 1.72

Throughout this notebook, I:

Implement a simple bigram language model to establish a baseline.
Gradually integrate more sophisticated attention techniques, including multi-head attention and positional encoding.
Compared the performance of the models at each stage to highlight the impact of these enhancements.
created a functional nanoGPT model that demonstrates the core principles of the Transformer architecture and showcases the power of attention mechanisms in natural language processing.
