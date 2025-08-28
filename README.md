# Predicting RNA:DNA Triplex Structures from Sequence Features Using Deep Learning Architectures

### By Joseph Luper Tsenum and Maria Poptsova

Correspondence Author's Email: tsenumjosephluper@phystech.edu

Phystech School of Biological and Medical Physics (FBMF)

Moscow Institute of Physics and Technology (National Research University)

Russian Federation


### Abstract

In this study, we developed fourteen (14) deep neural network models that predict the potential of lncRNAs and DNA sites to form triple helices on a genome-wide scale. To prepare our dataset, we first used Triplexator to screen out lncRNAs and DNA sites with low triplex-forming potential. We then trained different deep learning architectures, including two-layer convolutional neural networks (CNN), residual neural networks (ResNN), long short-term memory recurrent neural networks (LSTM-RNN), and multilayer perceptrons (MLP). Among these architectures, our lncRNA_CNN and LSTM3-RNN both achieved a mean AUC of 0.99 for lncRNA features at a kernel size of 32 and a learning rate of 1e-3. For DNA site features, our DNA_CNN achieved the best performance with a mean AUC of 0.98 under the same conditions. 

Our models revealed several novel lncRNAs and DNA sites—including HOTAIR, MEG3, PARTICLE, DACOR1, MIR100HG, FENDRR, ANRIL, TUG1, MALAT1, LINC00599, TINCR, NEAT1, roX2, DHFR, OTX2-AS1, Xist, SNHG16, ATXN8OS, BCYRN1, TERC, and Khps1 that have strong potential for forming triplex structures, thereby confirming and extending previous experimental and computational results. 

In conclusion, we demonstrate that deep neural network architectures can effectively learn sequence features of lncRNAs and DNA to accurately predict RNA:DNA triplex formation potential, providing a scalable in silico framework for studying genome-wide triplex biology. 
