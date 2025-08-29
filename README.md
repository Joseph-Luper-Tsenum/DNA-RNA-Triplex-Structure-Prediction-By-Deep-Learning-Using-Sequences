# Predicting RNA:DNA Triplex Structures from Sequence Features Using Deep Learning Architectures

### By Joseph Luper Tsenum and Maria Poptsova

Correspondence Author's Email: tsenumjosephluper@phystech.edu

Phystech School of Biological and Medical Physics (FBMF)

Moscow Institute of Physics and Technology (National Research University)

Russian Federation


### Abstract

Long non-coding RNAs (lncRNAs) can perform their regulatory roles by forming triple helices through RNA–DNA interactions. Although this has been verified by a few in vivo and in vitro methods, robust in silico approaches that predict the potential of lncRNAs and DNA sites to form triplex structures are still required. Tools such as Triplexator have predicted vast numbers of lncRNAs and DNA sites with triplex-forming potential, yet there remains a pressing need for advanced computational methods that can refine and extend these predictions. 

In this study, we developed fourteen (14) deep neural network models that predict the potential of lncRNAs and DNA sites to form triple helices on a genome-wide scale. To prepare our dataset, we first used Triplexator to screen out lncRNAs and DNA sites with low triplex-forming potential. We then trained different deep learning architectures, including two-layer convolutional neural networks (CNN), residual neural networks (ResNN), long short-term memory recurrent neural networks (LSTM-RNN), and multilayer perceptron (MLP). Among these architectures, our lncRNA_CNN and LSTM3-RNN both achieved a mean AUC of 0.99 for lncRNA features at a kernel size of 32 and a learning rate of 1e-3. For DNA site features, our DNA_CNN achieved the best performance with a mean AUC of 0.98 under the same conditions. 

In conclusion, we demonstrate that deep neural network architectures can effectively learn sequence features of lncRNAs and DNA to accurately predict RNA:DNA triplex formation potential, providing a scalable in silico framework for studying genome-wide triplex biology. 
