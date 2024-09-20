---

layout: page
permalink: /bioinformatics_in_action/index.html
title: bioinformatics_in_action
---

*This is for study and training for class Bioinformatics in Action 2024, Tsinghua University*

# Getting started

## 4 steps of bioinformatics

![1](./1.png)

### Question

#### Top 5 questions in *Science* 2005

1. what is the universe made of ?
2. what is the biological basis of consciousness?
3. why do humans have so few genes?
4. to what extent are genetic variation and personal health linked?
5. can the laws of physics be unified?

#### Top 3 philosophy questions

- what is life
- what is mind
- how universe works



### Information

#### Images

- Fluorescences
- Locations 
- 3D structures
- docking

#### Sequence

- DNA-seq

- RNA-seq

- Epigenetics

  - DNAase
  - Methylation
  - Histone modifications: ChIP-seq

- Interaction

  - Protein-DNA: ChIP-seq
  - Protein-RNA: CLIP-seq
  - DNA-RNA: Grid-seq

  

### Analysis

two keys: <mark>Data Clean & Feature Extraction<mark>

### Modeling

#### Types

- Math
  - Eg: $y=w_0+\sum_{i=1}^{N}w_ix_i$
- physics
  - Eg: thermo dynamics
- ...

#### Model VS Algorithm

|           |                   purpose                    |      Method      |
| :-------: | :------------------------------------------: | :--------------: |
|   Model   |       transform real problem into math       | Math and physics |
| Algorithm | translate math into computer logic elegantly |      Logic       |

### The Fourth Paradigm

![截屏2024-09-19 13.24.58](./截屏2024-09-19 13.24.58.png)

## Study Schedule

|    Date    |         Class         |                      My Own                       |
| :--------: | :-------------------: | :-----------------------------------------------: |
|  week 1-4  |  Basic Linux, Blast   |       Get familiar with docker, linux and R       |
|  week 5-9  |   NGS Data analysis   |           Strictly following the class            |
|  week 10   | Machine Learning & AI |  review python and strictly following the class   |
| week 11-16 |     SCS analysis      | follow the class while fulfilling the extra tasks |

# Lecture 1

## From Central dogma to bioinformatics

### 1D Study of <mark>DNA<mark>: How to Predict Genes from Raw Sequence?

#### A simple model

- given a stretch of genomic sequence
- preditc exons and introns

**HMM(hidden Markov Model)**: Voice Recognition-->DNA Gene Finder: Grammars

<img src="./HMM-6819002.png" alt="HMM" style="zoom: 33%;" />

## 2D study of <mark>RNA<mark>: Prediction of RNA Second Structure

**language of RNA: base pair**

- Trans-pairs
  - Interaction of 2 RNAs
- Cis-pairs
  - Folding of 1 RNA

**SCFG(stochastic context-free grammar)**: RNA 2^nd^ structure prediction

<img src="./SCFG.png" alt="SCFG" style="zoom:33%;" />

- intron 被splicesome剪成lariat(套索)

## 3D study of <mark>protein<mark>: Preditcion 3D structure of Protein from sequence

**Transformer(Large language model)**: Chat-GPT-->protein 3D structure

<img src="./p3dprediction.png" alt="p3dprediction" style="zoom:25%;" />

## 4D study of Precision Medicine: Early Cancer Screening

- 多组学多模态数据整合

  ![medicinemodel](./bioinformatics/images/medicinemodel.png)

  

