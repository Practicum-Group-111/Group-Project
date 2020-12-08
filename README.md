# Group-Project
Repo for the Group Projected To Be Submitted for the Practicum-1 course.

Group Number: 111

List of Group Members:
- Harshit Joshi (11911020 | CSE)
- Ayush Singh (11911004 | CSE)
- Rajkamal Shakya (11911069 | CSE)

## Original Research Paper

H. Hu, M. Liao, C. Zhang, & Y. Jing (2020). Text classification based recurrent neural network. In 2020 IEEE 5th Information Technology and Mechatronics Engineering Conference (ITOEC) (pp. 652-655).

[Link](https://ieeexplore.ieee.org/document/9141747) to the paper.

## Abstract

Recurrent neural networks (RNNs) have shown outstanding performance for natural language processing tasks, influenced by the repeated multiplication of the recurrent weight matrices, the problem of gradient vanishing and explosion problem will be encountered when training RNN. Independently recurrent neural network (IndRNN) makes neurons independent and constrains recursive weights to effectively solve gradient problems. We combine IndRNN with long short-term memory (LSTM) and attention model, and test it for text classification, the results show that our models can effectively adapt to text classification task.

## Our Solution
Adding an encoder layer for word representations. This increases the accuracy by 5.53%.

We use BERT(Bidirectional Encoder Representations from Transformers) which is pre tuned by Google.

[Link](https://github.com/google-research/bert) to the official BERT repo.

## Tools Used
- Python
- TensorFlow
- Google Colab
