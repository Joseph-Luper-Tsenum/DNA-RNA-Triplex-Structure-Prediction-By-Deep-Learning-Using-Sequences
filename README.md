# DNA-RNA-Triplex-Structure-Prediction-By-Deep-Learning-Using-Sequences

### By Joseph Luper Tsenum AND Maria Poptsova

Correspondence Author's Email: tsenumjosephluper@phystech.edu

Phystech School of Biological and Medical Physics (FBMF)

Moscow Institute of Physics and Technology (National Research University)

Russian Federation


### Introduction

Long non-coding RNAs (lncRNAs) can perform their regulatory roles by forming triple helices through RNA-DNA interaction. Although this has been verified by few in vivo and in vitro methods, in silico approaches that seek to predict the potentials of lncRNAs and DNA sites becoming a triplex forming structure is required. 

Triplexator have also predicted vast amounts of lncRNAs and DNA sites that has the potentials of becoming a triplex structure. There is also an emerging experimental evidence that the presence of epigenetic marks at DNA sites and lncRNAs can facilitate the formation of RNA:DNA triplex structures. There is therefore, a huge demand for computational approaches such as deep learning that can make novel predictions about RNA:DNA  triplex structure formation. 

In this study, we developed fourteen (14) deep neural network models that can predict the potentials of lncRNAs and DNA sites to form triple helices genome-wide, by taking lncRNAs, DNA sites, and histone modification marks as our features. While taking lncRNAs and DNA sites as our features, our data was first passed through the Triplexator to screen out lncRNAs and DNA sites with low potentials of forming triple helices. 

We used different deep learning architectures to build our models, including two-layer convolutional neural networks (CNN), residual neural networks (ResNN), long short term memory-recurrent neural networks (LSTM-RNN) and multilayer perceptron (MLP). Among these deep neural network architectures, our lncRNA_CNN and LSTM3-RNN both performed best at a mean AUC of 0.99 for the lncRNA features when 32 Kernel size and learning rate of 1e-3 was used. For our DNA site based-features, our DNA_CNN performed best at a mean AUC of 0.98 at 32 Kernel size and learning rate of 1e-3. Lastly, for our histone modification marks based-features, our DNA2_CNN performed best at a mean AUC of 0.78 at 32 Kernel size and learning rate of 1e-3. 

Our deep neural network models revealed several novel lncRNAs and DNA sites, including  HOTAIR, MEG3, PARTICLE, DACOR1, MIR100HG, FENDRR, ANRIL, TUG1, MALAT1, LINC00599, TINCR, NEAT1, roX2, DHFR, OTX2-AS1, Xist, SNHG16, ATXN8OS, BCYRN1, TERC, Khps1, that have the potential of forming triplex structures, thereby confirming previous experimental results and that of the Triplexator. The performance of our models also supports previous findings that histone modification marks can help in identifying lncRNAs and DNA regions that have the potentials of forming RNA:DNA triplex structures. In conclusion, we showed that different deep learning architectures can recognize lncRNAs and DNA that have the potentials of forming RNA:DNA triplex structures.
