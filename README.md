My partial thesis from my halted M.Sc. in computer science.

## Abstract:

Artificial Neural Networks (ANNs) are used in machine learning because they can be trained
to recognize handwriting or speech, control vehicles, or make predictions based on data. There
are two main approaches in the training of ANNs: supervised learning with the use of labelled
training data and using evolutionary algorithms to evolve the ANN, like neuroevolution. Neuroevolution
traditionally works with fixed topology networks, but one branch of neuroevolution allows adaption of
the network. One of the core ideas behind this type of neuroevolution is that the initial network is
minimal, and then additional structures will grow as necessary.

But unnecessary complexity increases the search space and slows the computing time required
to activate the network, especially in the case of recurrent connections. In the context of
neuroevolutionary pruning there are two important questions:
* Duration: when should pruning start, and how long should it continue? Should pruning
and complexification happen simultaneously?
* Mechanism: how should we determine the edge to be pruned? Should it be random or is
there a better way?

I investigate these questions in the context of NEAT, and look at a general way to improve
NEAT’s performance by pruning
