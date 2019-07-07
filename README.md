ML-Paper-Reading
---
a repo recording paper notes to encourage efficient paper reading.
---
# Preliminary: how to read a paper efficiently?(By Prof. Pete Carr)
## 1. Structure of a journal article:
    1). Title
    2). Keywords
    3). Abstract
    4). Introduction
    5). Experiment
    6). Results and discussion
    7). Summary/conclusions
    8). Reference

**Notes**: Don't read paper from the beginning to the end of the article. It's not a good use of your time.
## 2. A fairly simple algorithm to get the most out of the paper with the least effort with two phase process.
### First phase: how to survey the paper?
    1).Read the title and keywords
    2).Read the abstract
    3).Read the conclusions
### Second phase: how to read the paper?
    1).look at the tables and figures (including captions). This is what was done in the work.This doesn't take much time so it is worth looking at before really getting into details which will slow down the reading.
    2).Read the introduction. This is the background needed and why the study was done.
    3).Read the results and conclusions. This is the heart of the paper.
    4).Read the experiment. This is how they did the work. You only get to this point if you are really interested and need to understand exactly what was done to better understand the meaning of the data and its interpretation. 


At last, it's nececcary to write paper notes. **The faintest writing is better than the best memory!** 

# Outline
* [Preliminary knowledge](#1)
* [Reinforcement learning](#2)
* [Deep learning](#3)
* [Continual learning](#4)

<a name="1"/>

# Preliminary knowledge

[1] [Reinforcement learning: an introduction](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf)
* **Key word**: reinforcement learning
* **Authors**: Richard S. Sutton and Andrew G. Barto
* **Publish date**: 2018
* **Read date**: 2019/5/24
* **Tag**: textbook
* **Summary**: introduce basic reinforcement learning algorithm, about model based algorithm, value based method, policy gradient method and its variants, etc.
* **Pros**: basic and comprehensive.
* **Cons**: no exercise solution.

<a name="2"/>

# Reinforcement learning


<a name="3"/>

# Deep learning
[1] [SQUEEZENET: ALEXNET-LEVEL ACCURACY WITH
50 X FEWER PARAMETERS AND <0.5MB MODEL SIZE]()[[code](https://github.com/DeepScale/SqueezeNet)]
* **Key word**: 
* **Authors**: Forrest N.Iandola, Song Han, Matthew W. Moskewicz, Khalid Ashraf, William J. Dally, Kurt Keutzer
* **Publish date**: 2017
* **Read date**: 2019/7/7
* **Tag**: ICLR 2017
* **Summary**: 

    CNN MICROARCHITECTURE DESIGN SPACE EXPLORATION:
    * Strategy 1: Replace 3\*3 filters with 1\*1 filters.
    * Strategy 2: Decrease the number of input channels to 3\*3 filters. 
    * Strategy 3: Downsample late in the network so that convolution layers have large activation maps. 

    CNN MACROARCHITECTURE D ESIGN S PACE E XPLORATION:
    * SqueezeNet with simple bypass connections between some Fire modules.
    * SqueezeNet with complex bypass connections(1\*1 conv+simple bypass connections) between the remaining Fire modules. 
* **Conclusions**: 
    
    1.Toward this goal we have presented SqueezeNet, a CNN architecture that has 50× fewer parameters(vanilla SqueezeNet+Deep compression) than AlexNet and maintains AlexNet-level accuracy on ImageNet.

    2.Small models are more amenable to on-chip
implementations on FPGAs.

    3.SqueezeNet will be a good candidate CNN architecture for a variety of applications, especially those in which small model size is of importance.

* **Pros**: 

    1.Good movivation and well writting.
            
    2.Complementary experiments for ablation study and the hyper-parameters, such SR(squeeze ratio), pct_\{3\*3\}

    3.give some intuitition to design light weighted architecture.

* **Cons**: 
    
    1. Make more comparison with other light weighted architecture?
    
    2. It is not novel enough. 

<a name="4"/>

# Continual learning

[1] [Three scenarios for continual learning](https://arxiv.org/pdf/1904.07734.pdf)[[Code]](https://github.com/GMvandeVen/continual-learning)
* **Key word**: 
* **Authors**: Gido M. van de Ven, Andreas S. Tolias1
* **Publish date**: 2019
* **Read date**: 2019/6/2
* **Tag**: NeuraIPS workshop
* **Summary**: It is difficult to directly compare the performance of methods in different paper due to the difference in evaluation protocols. This papers describles three continual learning scenarios to enable more structures comparisons.Four continual learning methods(task-specific components,regularized optimization,modifying training data and using exemplars) are evaluated in these three scenarios(Task-IL, Domain-IL and Class-IL) in split MNIST and permunated MNIST.
* **Conclusions**:
* **Pros**: 
* **Cons**: 


