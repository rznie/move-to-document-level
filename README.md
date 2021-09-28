# A New Chapter for Neural Machine Translation: Moving to Document-level Period

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

This repository contains a list of papers, open-sourced codes, and datasets in Document-level NMT field which is carefully and comprehensively organized. If you found any error, please don't hesitate to open an issue or pull request.

![mind](dlt.png)

## Introduction

## Context-Aware Methods

### Why do we need context?

* Elena Voita, Rico Sennrich, Ivan Titov [When a Good Translation is Wrong in Context: Context-Aware Machine Translation Improves on Deixis, Ellipsis, and Lexical Cohesion](https://dx.doi.org/10.18653/v1/p19-1116)

Examples for disambiguation:

![examples](ex.png)
### What is _context_ ?

All these extra informations may be need during translation, and works in this section mainly focus on how to model these features in machine translations systems.

* Intra-sentential (within the current sentence)
* Inter-sentential (across multiple sentences)
* Extra-linguistic (e.g. social, temporal, cultural)

### How can we model context information?

* Encoder sides
  * Chih-Cheng Hung, Jiman Hong, Alessio Bechini, Eunjee Song and Ritam Mallick [Context- and sequence-aware convolutional recurrent encoder for neural machine translation](https://dl.acm.org/doi/10.1145/3412841.3442099)
  * Dual encoders
    * Jiacheng Zhang, Huanbo Luan, Maosong Sun, Feifei Zhai, Jingfang Xu [Improving the Transformer Translation Model with Document-Level Context](https://dx.doi.org/10.18653/v1/d18-1049)
  * Single Encoder
    * Shuming Ma, Dongdong Zhang, Ming Zhou [A Simple and Effective Unified Encoder for Document-Level Machine Translation](https://dx.doi.org/10.18653/v1/2020.acl-main.321)
* Decoder sides
  * Decoding with context
    * Hayahide Yamagishi, Mamoru Komachi [Improving Context-aware Neural Machine Translation with Target-side Context](https://arxiv.org/abs/1909.00531)
  * Language model
    * Amane Sugiyama, Naoki Yoshinaga [Context-aware Decoder for Neural Machine Translation using a Target-side Document-Level Language Model](https://arxiv.org/abs/2010.12827)
* Extend Memory
  * Zhaopeng Tu, Yang Liu, Shuming Shi, Tong Zhang [Learning to Remember Translation History with a Continuous Cache](https://arxiv.org/abs/1711.09367)
* Embeddings
  * Valentin Hofmann, Janet B Pierrehumbert and Hinrich Schütze [Dynamic Contextualized Word Embeddings](https://arxiv.org/abs/2010.12684)
* With Graph Network
  * Mingzhou Xu, Liangyou Li, Derek F Wong, Qun Liu and Lidia S Chao [Document Graph for Neural Machine Translation](https://arxiv.org/abs/2012.03477)
* with Pre-trained model
  * Domenic Donato, Lei Yu and Chris Dyer [Diverse Pretrained Context Encodings Improve Document Translation](https://arxiv.org/abs/2106.03717)
  * Hassan S Shavarani, Anoop Sarkar [Better Neural Machine Translation by Extracting Linguistic Information from BERT](https://arxiv.org/abs/2104.02831)
  * Rongxiang Weng, Heng Yu, Shujian Huang, Shanbo Cheng, Weihua Luo [Acquiring Knowledge from Pre-trained Model to Neural Machine Translation](https://arxiv.org/abs/1912.01774)
* Others
  * Lei Yu, Laurent Sartran, Wojciech Stokowiec, Wang Ling and Lingpeng Kong [Better Document-Level Machine Translation with Bayes' Rule](https://arxiv.org/abs/1910.00553)
  * Lesly Miculicich, Dhananjay Ram, Nikolaos Pappas and James Henderson [Document-Level Neural Machine Translation with Hierarchical Attention Networks](https://dx.doi.org/10.18653/v1/d18-1325)
  * Pei Zhang, Boxing Chen, Niyu Ge and Kai Fan [Long-Short Term Masking Transformer: A Simple but Effective Baseline for Document-level Neural Machine Translation](https://arxiv.org/abs/2009.09127)
  * Elena Voita, Rico Sennrich and Ivan Titov [Context-Aware Monolingual Repair for Neural Machine Translation](https://www.aclweb.org/anthology/D19-1081)
  * Inigo Jauregi Unanue, Nazanin Esmaili, Gholamreza Haffari and Massimo Piccardi [Leveraging Discourse Rewards for Document-Level Neural Machine Translation](https://arxiv.org/abs/2010.03732)

### Are these models actually using context?

* Kayo Yin, Patrick Fernandes, Danish Pruthi, Aditi Chaudhary, André F T Martins [Do Context-Aware Translation Models Pay the Right Attention?](https://arxiv.org/abs/2105.06977)
* Patrick Fernandes, Kayo Yin, Graham Neubig, André F T Martins [Measuring and Increasing Context Usage in Context-Aware Machine Translation](https://arxiv.org/abs/2105.03482)
* Bei Li, Hui Liu, Ziyang Wang, Yufan Jiang and Tong Xiao [Does Multi-Encoder Help? A Case Study on Context-Aware Neural Machine Translation](https://aclanthology.org/2020.acl-main.322)
* Yunsu KimDuc Thanh TranHermann Ney [When and Why is Document-level Context Useful in Neural Machine Translation?](https://arxiv.org/abs/1910.00294)
* Mat ̄ıss Rikters and Toshiaki Nakazawa [Revisiting Context Choices for Context-aware Machine Translation]()
* Joe O'Connor, Jacob Andreas [What Context Features Can Transformer Language Models Use?](https://arxiv.org/abs/2106.08367)

### Can we encourage them to do better?

* Xiaomian Kang, Yang Zhao, Jiajun Zhang, Chengqing Zong [Dynamic Context Selection for Document-level Neural Machine Translation via Reinforcement Learning](https://arxiv.org/abs/2010.04314)
* Long Zhang, Tong Zhang, Haibo Zhang, Baosong Yang, Wei Ye [Multi-Hop Transformer for Document-Level Machine Translation](https://dx.doi.org/10.18653/v1/2021.naacl-main.309)
* Zaixiang Zheng, Xiang Yue, Shujian Huang, Jiajun Chen and Alexandra Birch [Towards Making the Most of Context in Neural Machine Translation](https://www.ijcai.org/proceedings/2020/551)
* Sameen Maruf, André F T Martins, Gholamreza Haffari [Selective Attention for Context-aware Neural Machine Translation](https://aclweb.org/anthology/N19-1313)
* Liangyou Li and Xin Jiang and Qun Liu [Pretrained Language Models for Document-Level Neural Machine Translation](https://arxiv.org/abs/1911.03110)
* Long Zhang, Tong Zhang, Haibo Zhang, Baosong Yang, Wei Ye [Multi-Hop Transformer for Document-Level Machine Translation](https://aclanthology.org/2021.naacl-main.309.pdf)
* Hao Xiong, Zhongjun He, Hua Wu, Haifeng Wang [Modeling Coherence for Discourse Neural Machine Translation](https://wvvw.aaai.org/ojs/index.php/AAAI/article/view/4721)
* Lorenzo Lupo, Marco Dinarelli, Laurent Besacier [Divide and Rule: Training Context-Aware Multi-Encoder Translation Models with Little Resources](https://arxiv.org/abs/2103.17151)

## Document-level Solutions

* Doc2doc transformers
  * Zewei Sun, Mingxuan Wang, Hao Zhou, Chengqi Zhao, Shujian Huang, Jiajun Chen, Lei Li [Capturing Longer Context for Document-level Neural Machine Translation: A Multi-resolutional Approach](https://arxiv.org/pdf/2010.08961.pdf)
* G-transformers
  * Guangsheng Bao, Yue Zhang, Zhiyang Teng, Boxing Chen, Weihua Luo [G-Transformer for Document-level Machine Translation](https://arxiv.org/abs/2105.14761)
* Mbart
  * Yinhan Liu, Jiatao Gu, Naman Goyal, Xian Li, Sergey Edunov, Marjan Ghazvininejad, Mike Lewis, Luke Zettlemoyer [Multilingual Denoising Pre-training for Neural Machine Translation](https://arxiv.org/abs/2001.08210)
* Training Objectives
  * Danielle Saunders, Felix Stahlberg, Bill Byrne [Using Context in Neural Machine Translation Training Objectives](https://arxiv.org/abs/2005.01483)
* Zewei Sun, Mingxuan Wang, Hao Zhou, Chengqi Zhao, Shujian Huang [Capturing Longer Context for Document-level Neural Machine Translation: A Multi-resolutional Approach](https://arxiv.org/abs/2010.08961)
* Iz Beltagy, Matthew E Peters and Arman Cohan [Longformer: The Long-Document Transformer](https://arxiv.org/abs/2004.05150)

## Dataset

* Matīss Rikters, Ryokan Ri, Tong Li and Toshiaki Nakazawa [Document-aligned Japanese-English Conversation Parallel Corpus](https://arxiv.org/abs/2012.06143)

## Evaluation

* Nitika Mathur, Timothy Baldwin and Trevor Cohn [Tangled up in BLEU: Reevaluating the Evaluation of Automatic Machine Translation Evaluation Metrics](https://dx.doi.org/10.18653/v1/2020.acl-main.448)
* Lesly Miculicich Werlen, Andrei Popescu-Belis [Validation of an Automatic Metric for the Accuracy of Pronoun Translation (APT)](https://aclanthology.org/W17-4802)
* Elena Voita, Rico Sennrich and Ivan Titov [When a Good Translation is Wrong in Context: Context-Aware Machine Translation Improves on Deixis, Ellipsis, and Lexical Cohesion](https://www.aclweb.org/anthology/P19-1116)
* B. T. M. Wong, C. F. K. Pun, C. Kit, J. J. Webster [Lexical cohesion for evaluation of machine translation at document level](https://ieeexplore.ieee.org/document/6138201/)
* Prathyusha Jwalapuram, Shafiq Joty, Irina Temnikova and Preslav Nakov [Evaluating Pronominal Anaphora in Machine Translation: An Evaluation Measure and a Test Suite](https://aclanthology.org/D19-1294)
* Yuchen JiangShuming MaDongdong ZhangJian YangHaoyang Huang [BlonD: An Automatic Evaluation Metric for Document-level MachineTranslation](https://arxiv.org/abs/2103.11878)

## Surveys & Comparisons

* Sameen Maruf, Fahimeh Saleh and Gholamreza Haffari [A Survey on Document-level Neural Machine Translation: Methods and Evaluation](https://dl.acm.org/doi/10.1145/3441691)
* Zhiyi Ma, Sergey Edunov and Michael Auli [A Comparison of Approaches to Document-level Machine Translation](https://arxiv.org/abs/2101.11040)
* Jingjing Huo, Christian Herold, Yingbo Gao, Leonard Dahlmann and Shahram Khadivi [Diving Deep into Context-Aware Neural Machine Translation](https://arxiv.org/abs/2010.09482)