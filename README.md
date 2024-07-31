Typically, as a neural network's performance on training data improves, its performance on (un-
seen) validation data also improves until the network starts overtting.However, grokking, a
recently discovered phenomenon by , defies this norm by showing a sudden and dramatic
improvement in validation performance long after overtting has begun. This delayed general-
ization pattern has been notably observed in algorithmic tasks like modular addition. Grokking
is sometimes viewed as a phase change in the network's learning process.
In this project, we explore the concept of grokking in the context of modular addition, examining its occurrence in
dierent types of neural networks and training setups. We discovered that groking happens in
many types of models and is inuenced by the amount of training data used. Specically, we con-
duct our experiments in recurrent neural networks (RNNs) and long short-term memory (LSTM)
networks. Additionally, our results show that using regularization techniques such as weight decay
can help the models generalize better. Our observations indicate that training without weight
decay leads to poor generalization and that removing weight decay too early also has the same
eect. Moreover, we demonstrate that weight decay is not necessary during the early phases of
training. Introducing weight decay only late in training still leads to grokking, which is a novel
discovery. These experiments aim to provide deeper insights into the factors that aect grokking.
