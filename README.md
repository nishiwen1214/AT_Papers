# Adversarial training papers
  
![](https://img.shields.io/github/stars/nishiwen1214/AT_Papers?style=flat-square)
![](https://img.shields.io/badge/PaperNumber-16-brightgreen)


Must-read papers on Adversarial training for neural network models. The paper list is mantained by [Shiwen Ni](https://github.com/nishiwen1214/).

## Contents

- [Adversarial training papers](#adversarial-training-papers)
  - [Contents](#contents)
  - [Introduction](#introduction)
  - [Papers](#papers)
    - [Recommended Papers](#recommended-papers)
    - [General Paper](#general-paper)

## Introduction

This is a paper list about **Adversarial training** for neural network models. Note that the [recommended papers](#recommended-papers) are those that I have read and found to be good.


## Papers

### Recommended Papers

1. **Explaining and Harnessing Adversarial Examples**, ICLR 2015.  ![](https://img.shields.io/badge/Generalization-green) ![](https://img.shields.io/badge/Robustness-blue) ![](https://img.shields.io/badge/First_paper-red)

   *Ian J. Goodfellow, Jonathon Shlens, Christian Szegedy* [[pdf](https://arxiv.org/pdf/1412.6572.pdf)], [[code](https://github.com/facebookarchive/adversarial_image_defenses)], **(FGSM)**.

2. **Adversarial Training Methods for Semi-Supervised Text Classification**, ICLR 2017.  ![](https://img.shields.io/badge/Generalization-green) ![](https://img.shields.io/badge/Text-red)

   *Takeru Miyato, Andrew M. Dai, Ian Goodfellow* [[pdf](https://arxiv.org/pdf/1605.07725.pdf)], [[code](https://github.com/tensorflow/models)], **(FGM)**.

3. **Obfuscated Gradients Give a False Sense of Security: Circumventing Defenses to Adversarial Examples**, ICML 2018. ![](https://img.shields.io/badge/Robustness-blue)![](https://img.shields.io/badge/K_step-red)

   *Anish Athalye, Nicholas Carlini, David Wagner* [[pdf](https://arxiv.org/pdf/1802.00420.pdf)], [[code](https://github.com/anishathalye/obfuscated-gradients)], **(PGD)**.
   
4. **Adversarial Training for Free!**, NeurIPS 2019.  ![](https://img.shields.io/badge/Generalization-green) ![](https://img.shields.io/badge/Free-blue)

   *Ali Shafahi, Mahyar Najibi, Amin Ghiasi, Zheng Xu, John Dickerson, Christoph Studer, Larry S. Davis, Gavin Taylor, Tom Goldstein* [[pdf](https://arxiv.org/pdf/1904.12843.pdf)], [[code](https://github.com/mahyarnajibi/FreeAdversarialTraining)], **(FreeAT)**.

5. **You Only Propagate Once: Accelerating Adversarial Training via Maximal Principle**, NeurIPS 2019.  ![](https://img.shields.io/badge/Generalization-green) ![](https://img.shields.io/badge/accelerate-blue) 

   *Dinghuai Zhang, Tianyuan Zhang, Yiping Lu, Zhanxing Zhu, Bin Dong* [[pdf](https://arxiv.org/pdf/1905.00877.pdf)], [[code](https://github.com/a1600012888/YOPO-You-Only-Propagate-Once)], **(YOPO)**.
   
6. **FreeLB: Enhanced Adversarial Training for Natural Language Understanding**, ICLR 2020.  ![](https://img.shields.io/badge/Generalization-green) ![](https://img.shields.io/badge/Free-blue) ![](https://img.shields.io/badge/text-red)

   *Chen Zhu, Yu Cheng, Zhe Gan, Siqi Sun, Tom Goldstein, Jingjing Liu* [[pdf](https://arxiv.org/pdf/1909.11764.pdf)], [[code](https://github.com/zhuchen03/FreeLB)], **(FreeLB)**.
   
 7. **DropAttack: A Masked Weight Adversarial Training Method to Improve Generalization of Neural Networks**, ArXiv 2021.  ![](https://img.shields.io/badge/Generalization-green) ![](https://img.shields.io/badge/Masked-blue) ![](https://img.shields.io/badge/text-red)
    
    *Shiwen Ni, Jiawen Li, Hung-Yu Kao* [[pdf](https://arxiv.org/pdf/2108.12805.pdf)], [[code](https://github.com/nishiwen1214/dropattack)], **(DropAttack)**.  
   
### General Paper

 1. [**What Doesn't Kill You Makes You Robust(er): Adversarial Training against Poisons and Backdoors**](https://arxiv.org/pdf/2102.13624.pdf)

    *Jonas Geiping, Liam Fowl, Gowthami Somepalli, Micah Goldblum, Michael Moeller, Tom Goldstein*, 2021.
 2. [**Attacks Which Do Not Kill Training Make Adversarial Learning Stronger**](https://arxiv.org/pdf/2002.11242.pdf)

    *Jingfeng Zhang, Xilie Xu, Bo Han, Gang Niu, Lizhen Cui, Masashi Sugiyama, Mohan Kankanhalli*, ICML 2020.
    
 3. [**On the Convergence and Robustness of Adversarial Training**](http://proceedings.mlr.press/v97/wang19i/wang19i.pdf)

    *Yisen Wang, Xingjun Ma, James Bailey, Jinfeng Yi, Bowen Zhou, Quanquan Gu*, ICML 2019.
    
 4. [**Curriculum Adversarial Training**](https://arxiv.org/pdf/1805.04807.pdf)

    *Yisen Wang, Xingjun Ma, James Bailey, Jinfeng Yi, Bowen Zhou, Quanquan Gu*, IJCAI 2018.
    
 5. [**Rademacher Complexity for Adversarially Robust Generalization**](http://proceedings.mlr.press/v97/yin19b/yin19b.pdf)

    *Dong Yin, Ramchandran Kannan, Peter Bartlett*, ICML 2019.
 
 6. [**Deep Defense: Training DNNs with Improved Adversarial Robustness**](https://arxiv.org/pdf/1803.00404.pdf)

    *Ziang Yan, Yiwen Guo, Changshui Zhang*, NeurIPS 2018.  

 7. [**Single-Step Adversarial Training With Dropout Scheduling**](https://ieeexplore.ieee.org/abstract/document/9157154/authors#authors)

    *B. S. Vivek; R. Venkatesh Babu*, CVPR 2020. 
    
 8. [**Adversarial Training and Provable Defenses: Bridging the Gap**](https://openreview.net/pdf?id=SJxSDxrKDr)

    *Mislav Balunovic, Martin Vechev*, ICLR 2020. 

 9. [**Adversarial Examples: Attacks and Defenses for Deep Learning**](https://ieeexplore.ieee.org/abstract/document/8611298)

    *Xiaoyong Yuan; Pan He; Qile Zhu; Xiaolin Li*, TNNLS 2019. 
