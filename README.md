# SNN-Evolutionary-Ensemble
## Training Spiking Neural Networks using an Ensemble of Nature-Inspired Algorithms 

Spiking Neural Networks often called as the third generation of neural networks are bio-inspired ANN
where information is encoded as discrete spikes in time[1]. The input and outputs of Spiking Neural
Networks are encoded in the form of spike trains. The primary idea behind Spiking Neural Networks
(SNN) is that the human brain encodes information in the form of spikes and these spikes induce
potentials in the neurons which helps them fire and produce an output to a corresponding input.
The spike events are discrete in time, hence application of supervised learning algorithms are difficult.
Majority of the learning algorithms in case of Spiking Neural Networks are based on the principle of
Hebbian Learning. Over the years, some supervised learning algorithms like SpikeProp[2], SPAN[3],
ReSuMe[4] have been developed by approximating the discrete signals to a continuous one. Since
SNNs are inspired by the brain and supervised learning algorithms are difficult to implement, nature
or bio-inspired algorithms can play an important role during the learning phase of SNNs. Particle
swarm optimization algorithms have been used previously to learn the synaptic weights in case of
Spiking Neural Networks[5].
Ensemble learning is a technique where multiple learners are used to solve some instance of a problem.
Ensemble learners have been shown to outperform single classiers [6]. Genetic algorithms have been
used in the past to determine the optimal set of weights for each learning algorithm in an ensemble
setting. Ensemble of various bio-inspired algorithms to solve a particular instance has never been
done before, and hence a mixture of various bio-inspired algorithms to train Spiking Neural Networks
is an approach that still remains to be investigated. Therefore this project would revolve about using
an ensemble of various existing bio-inspired algorithms to determine the optimal sets of weights of a
Spiking Neural Network and evaluating the performance of such an ensemble setting. Three different evolutionary
algorithms are used 

### References
[1] S. Thorpe, D. Fize, C. Marlot, Speed of processing in the human visual system. Nature 381
(6582), 520522 (1996)

[2] S.M. Bohte, J.N. Kok, H. La Poutre, SpikeProp : Backpropagation for Networks of Spiking
Neurons Error-Backpropagation in a Network of Spiking Neurons. ESANN (2000), pp. 419 424

[3] A. Mohemmed, S. Schliebs, S. Matsuda, N. Kasabov, SPAN: spike pattern association neuron for
learning spatio-temporal sequences. Int. J. Neural Syst. 22(4), 116 (2012)

[4] F. Ponulak, ReSuMenew supervised learning method for spiking neural networks. Tech. report,
Institute of Control and Information Engineering, Pozna University of Technology, Pozna, Poland
(2005)

[5] A. Mohemmed, S. Schliebs, S. Matsuda, K. Dhoblea, N. Kasabov (2011), Optimization of spiking
neural networks with dynamic synapses for spike sequence generation using PSO, in International
Joint Conference on Neural Networks. IEEE Publishing, San Jose, California, USA (2011)

[6] Chandra, A. Yao, X. J Math Model Algor (2006) 5: 417. https://doi.org/10.1007/s10852-005-
9020-3