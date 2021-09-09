# A New Chapter for Neural Machine Translation: Moving to Document-level Period

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 

This repository contains a list of papers, open-sourced codes, and datasets in Document-level NMT field which is carefully and comprehensively organized. If you found any error, please don't hesitate to open an issue or pull request.

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
* extra-linguistic (e.g. social, temporal, cultural)

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

<div style="overflow-x: auto; overflow-y: auto; height: auto; width:100%;">
<table style="width:100%" border="2">
<thead>
  <tr>
    <th>Name</th>
    <th>Intro</th>
    <th>Links</th>
    <th>Detail</th>
    <th>Size & Stats</th>
  </tr>
</thead>
<tbody >
<tr>
	<td><code> Restaurant dataset                         </td></code>
		<td> Collected by a spoken dialogue system providing information about certain venues in San Francisco </td>
		<td> Download： https://github.com/shawnwun/RNNLG   Paper： https://arxiv.org/pdf/1508.01745.pdf</td>
		<td> Restaurant Information;Dialogue act types: 8  Slots: 12 Dialogue acts: 248 </td>
		<td> Dialogues: around 1k  Utterances: around 5192   the ratio of training, validation, and testing set: 3:1:1     </td>
</tr>

## Evaluation