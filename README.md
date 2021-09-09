# A New Chapter for Neural Machine Translation: Moving to Document-level Solutions

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

This repository contains a list of papers, open-sourced codes, datasets and leaderboards in NLG field which is carefully and comprehensively organized. If you found any error, please don't hesitate to open an issue or pull request.

* Diederik P. Kingma, Jimmy Ba. 2015. [Adam: A Method for Stochastic Optimization](https://arxiv.org/pdf/1412.6980). In *Proceedings of ICLR 2015*. 

![mind](dlt.png)

## Introduction

## Context-Aware Methods

### Why do we need context?

examples for Disambiguation

### What is _context_ ?

All these extra informations may be need during translation, and works in this section mainly focus on how to model these features in machine translations systems.

* intra-sentential (within the current sentence)
* inter-sentential (across multiple sentences)
* extra-linguistic (e.g. social, temporal, cultural) level

### How can we model context information?

* Encoder sides
  * dual encoders
  * single Encoder
* Decoder sides
  * decoding with context
  * language model
* Extend Memory

### How much are these models actually using?

CXMI

### Can we encourage them to do better?

future works

## Document-level Solutions

* Doc2doc transformers
* G-transformers
* Mbart

## Dataset

## Evaluation