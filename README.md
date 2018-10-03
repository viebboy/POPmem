# Progressive Operational Perceptron with Memory
ArXiv: https://arxiv.org/abs/1808.06377

Short description: Generalized Operational Perceptron (GOP) was proposed to generalize the linear neuron model in the traditional Multilayer Perceptron (MLP) and this model can mimic the synaptic connections of the biological neurons that have nonlinear neurochemical behaviours. Progressive Operational Perceptron (POP) is a multilayer network composing of GOPs which is formed layer-wise progressively. In this work, we propose major modifications that can accelerate (POPfast) as well as augment the progressive learning procedure of POP by incorporating an information-preserving, linear projection path from the input to the output layer at each progressive step (POPmem-H/ POPmem-O). The proposed extensions can be interpreted as a mechanism that provides direct information extracted from the previously learned layers to the network, hence the term ``memory". An extensive set of experiments show that the proposed modifications can surpass the learning capability of the original POPs and other related algorithms([BLS](https://ieeexplore.ieee.org/document/7987745/), [PLN](https://arxiv.org/abs/1710.08177), [S-ELM](https://ieeexplore.ieee.org/document/6937189/))

# Source Code


The source code for POPmem has been integrated into our new python package for GOP-based algorithms called [PyGOP](https://github.com/viebboy/PyGOP)
