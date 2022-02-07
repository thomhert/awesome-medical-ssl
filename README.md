# Awesomne Medical Self-Supervised Learning[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Medical Self-Supervised Learning resources. Copy githhub format from: [awesome-self-supervised-learning Zhongzheng Ren](https://github.com/jason718/awesome-self-supervised-learning).

Inspired by [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning), [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), 

#### Why Self-Supervised?
Self-Supervised Learning has become an exciting direction in AI community. 
  - Jitendra Malik: "Supervision is the opium of the AI researcher"
  - Alyosha Efros: "The AI revolution will not be supervised"
  - Yann LeCun: "self-supervised learning is the cake, supervised learning is the icing on the cake, reinforcement learning is the cherry on the cake"

## Contributing
<p align="center">
  <img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://thomhert.github.io/) or add [pull request](https://github.com/thomhert/awesome-medical-ssl/pulls)


Markdown format:
```markdown
- Paper Name. 
  [[pdf]](link) 
  [[code]](link)
  - Author 1, Author 2, and Author 3. *Conference Year*
```


## Table of Contents
- [Theory](#theory)
- [Computer Vision (CV)](#computer-vision)
  - [Survey](#survey)
  - [Image Representation Learning](#image-representation-learning)
  - [Video Representation Learning](#video-representation-learning)
  - [Geometry](#geometry)
  - [Audio](#audio)
  - [Others](#others)
- [Machine Learning](#machine-learning)
  - [Reinforcement Learning](#reinforcement-learning)
  - [Recommendation Systems](#recommendation-systems)
- [Robotics](#robotics)  
- [Natural Language Processing (NLP)](#nlp)
- [Automatic Speech Recognition (ASR)](#asr)
- [Graph](#graph)
- [Talks](#talks)
- [Thesis](#thesis)
- [Blog](#blog)


## Theory    
-   A Theoretical Analysis of Contrastive Unsupervised Representation Learning.
    [[pdf]](https://arxiv.org/pdf/1902.09229.pdf)
    -   Sanjeev Arora, Hrishikesh Khandeparkar, Mikhail Khodak, Orestis Plevrakis, and Nikunj Saunshi. *ICML 2019*

-   Understanding the Behaviour of Contrastive Loss.
    [[pdf]](https://arxiv.org/pdf/2012.09740.pdf)
    -   Feng Wang and Huaping Liu. *CVPR 2021*
    
-   Predicting What You Already Know Helps: Provable Self-Supervised Learning. 
    [[pdf]](https://arxiv.org/pdf/2008.01064.pdf)
    -   Jason D. Lee, Qi Lei, Nikunj Saunshi, and Jiacheng Zhuo.

-   Contrastive learning , multi-view redundancy , and linear models.
    [[pdf]](https://arxiv.org/pdf/2008.10150.pdf)
    -   Christopher Tosh, Akshay Krishnamurthy, and Daniel Hsu.
   
-   Understanding Self-supervised Learning with Dual Deep Networks.
    [[pdf]](https://arxiv.org/pdf/2010.00578.pdf)
    -   Yuandong Tian, Lantao Yu, Xinlei Chen, and Surya Ganguli.
    
-   For self-supervised learning, Rationality implies generalization, provably.
    [[pdf]](https://arxiv.org/pdf/2010.08508.pdf)
    -   Yamini Bansal, Gal Kaplun, and Boaz Barak.
   
-   Can Pretext-Based Self-Supervised Learning Be Boosted by Downstream Data? A Theoretical Analysis.
    [[pdf]](https://arxiv.org/pdf/2103.03568.pdf)
    -   Jiaye Teng and Weiran Huang.
       
       
## Computer Vision
### Survey
- Contrastive Representation Learning: A Framework and Review
  [[pdf]](https://arxiv.org/abs/2010.05113)
  - Phuc H. Le-Khac, Graham Healy, Alan F. Smeaton. *IEEE Access 2020*

- A Survey on Contrastive Self-supervised Learning
  [[pdf]](https://arxiv.org/pdf/2011.00362.pdf)
  - Ashish Jaiswal, Ashwin R Babu, Mohammad Z Zadeh, Debapriya Banerjee, Fillia Makedon

- Self-supervised Visual Feature Learning with Deep Neural Networks: A Survey.
  [[pdf]](https://arxiv.org/pdf/1902.06162.pdf)
  - Longlong Jing and Yingli Tian. *T-PAMI 2020*

- Self-supervised Learning: Generative or Contrastive
  [[pdf]](https://arxiv.org/pdf/2006.08218.pdf)
  - Xiao Liu, Fanjin Zhang, Zhenyu Hou, Li Mian, Zhaoyu Wang, Jing Zhang, Jie Tang.


### Image Representation Learning

#### Benchmark code
- FAIR Self-Supervision Benchmark [[pdf]](https://arxiv.org/abs/1905.01235) [[repo]](https://github.com/facebookresearch/fair_self_supervision_benchmark): various benchmark (and legacy) tasks for evaluating quality of visual representations learned by various self-supervision approaches.

- How Well Do Self-Supervised Models Transfer? [[pdf]](https://arxiv.org/abs/2011.13377) [[repo]](https://github.com/linusericsson/ssl-transfer): A benchmark for evaluating self-supervision consisting of many-shot/few-shot recognition, object detection, surface normal estimation and semantic segmentation.
    

#### 2020
 - A critical analysis of self-supervision, or what we can learn from a single image
   [[pdf]](https://arxiv.org/pdf/1904.13132)
   [[code]](https://github.com/yukimasano/linear-probes)
   - Yuki M. Asano, Christian Rupprecht, Andrea Vedaldi. *ICLR 2020*
 

#### 2021

 - Contrastive Semi-Supervised Learning for 2D Medical Image Segmentation
   [[pdf]](https://arxiv.org/abs/2106.06801)
   - Prashant Pandey, Ajey Pai, Nisarg Bhatt, Prasenjit Das, Govind Makharia, Prathosh AP, Mausam. *MICCAI 2021*

### Video Representation Learning

### Geometry

### Audio

### Others

## Machine Learning
-   Self-taught Learning: Transfer Learning from Unlabeled Data.
    [[pdf]](https://ai.stanford.edu/~hllee/icml07-selftaughtlearning.pdf)
    -   Raina, Rajat and Battle, Alexis and Lee, Honglak and Packer,
        Benjamin and Ng, Andrew Y. *ICML 2007*

-   Representation Learning: A Review and New Perspectives.
    [[pdf]](https://arxiv.org/pdf/1206.5538.pdf)
    -   Bengio, Yoshua and Courville, Aaron and Vincent, Pascal. *TPAMI 2013*.

### Reinforcement Learning

### Recommendation Systems

## Robotics

## NLP

## ASR

## Graph   
 - Gaining insight into SARS-CoV-2 infection and COVID-19 severity using self-supervised edge features and Graph Neural Networks
    [[pdf]](https://arxiv.org/pdf/2006.12971v1.pdf)
   - Arijit Sehanobish, Neal G. Ravindra, David van Dijk. *ICML 2020 Workshop*

## Talks

## Thesis


## Blog
- Self-Supervised Representation Learning. Lilian Weng. [[link]](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html).
- Contrastive Self-Supervised Learning. Ankesh Anand. [[link]](https://ankeshanand.com/blog/2020/01/26/contrative-self-supervised-learning.html).

## License
To the extent possible under law, [Thomhert](https://thomhert.github.io/) has waived all copyright and related or neighboring rights to this work.

