# How do Deep Neural Networks compare to fMRI representations of the brain?

Neuromatch Academy Computational Neuroscience 2021 project by Alexander Enge, Manshan Guo, Fabian Renz, Regina Zaghi-Lara and Katherine Baquero

Special credit to our TAs:  Patrick Boak and Tejas Savalia

And to our mentor: Steven Scholte 
 
 ## Abstract

Deep artificial neural networks (DNNs) can serve as candidate models for human visual processing. These models allow the exploration of behavioral tasks in both biological and computer vision (Lindsay, G. 2020; Kar, K. et al. 2018). In recent years, a variety of such DNNs have been developed, from simple feedforward architectures like AlexNet (Krizhevsky, A. et al. 2012)  to more complex ones like Residual Neural Networks (ResNets; He, K. et al. 2015). What remains unclear is what neural network design choices are most appropriate for modelling human visual processing (Tal, G. et al. 2020). Here, we employ representational similarity analysis (RSA) to compare different choices of state-of-the-art DNN architectures to human fMRI responses in the early visual cortex (EVC) and inferotemporal cortex (IT; Cichy et al., 2014). Using RSA, one can show the same stimuli (e.g., images of natural objects) to humans and DNNs and probe the degree to which different brain areas and network layers represent visual information in a similar fashion. It,  therefore, allowed us to disentangle the importance of two choices in DNN design—model complexity and supervision—in accounting for the brain representations as measured with fMRI. For model complexity, we expected deeper networks (ResNet) to explain more variance than shallower networks (AlexNet). For the model supervision, we expected unsupervised networks (MoCo) to explain more variance than their supervised counterparts (ResNet). By making these comparisons, we hope to gain a better understanding of the required model complexity, as well as the appropriate learning type for modeling human visual processing.

Lindsay, G. 2020. Convolutional Neural Networks as a Model of the Visual System: Past, Present, and Future. Journal of Cognitive Neuroscience X:Y, pp. 1–15 https://doi.org/10.1162/jocn_a_01544 

Krizhevsky, A. et al. 2017. ImageNet Classification with Deep Convolutional Neural Networks. Communications of the ACM. 60:6, 84-90. https://doi.org/10.1145/3065386

Kar, K. et al. 2018. Evidence that recurrent circuits are critical to the ventral stream’s execution of core object recognition behavior.  BiorXiv. doi: https://doi.org/10.1101/354753.  

He, K. et al. 2015. Deep Residual Learning for Image Recognition. ArXiv. https://arxiv.org/pdf/1512.03385.pdf

Tal, G. et al. 2020. Controversial Stimuli: Pitting Neural Networks against each other as models of human recognition. ArXiv. https://arxiv.org/pdf/1911.09288.pdf
