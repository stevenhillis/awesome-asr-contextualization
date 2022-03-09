# Awesome Contextualization of E2E ASR [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Contribution](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/stevenhillis/awesome-asr-contextualization/blob/main/CONTRIBUTING.md)

> Curated list of awesome papers on Contextualization of E2E ASR. 

The purpose of contextualizating ASR outputs is to bias the results towards tokens, generally proper nouns or rare words or jargon, which are thought likely to be produced given the context of an audio signal. Correct transcription of these tokens might have an outsized impact on the value of the output, and incorrect transcription might otherwise be likely.

To add items to this page, open up a pull request according to our [contributing guide](CONTRIBUTING.md).

## Contents

* [Deep Contextualization](#Deep-Contextualization)
  * [Contextual LAS](#Contextual-LAS-(CLAS))
  * [Contextual Transducer](#Contextual-Transducer-("RNNTs"))
  * [2021](#2021)
  * [2022](#2022)
* [External Contextualization](#External-Contextualization)
  * [2012](#2012)
  * [2015](#2015)
  * [2016](#2016)
  * [2017](#2017)
  * [2018](#2018)
  * [2019](#2019)
  * [2020](#2020)
  * [2021](#2021)

## Deep Contextualization
End to end approaches, integrated neural modules

### Contextual LAS (CLAS)

* [Deep context: end-to-end contextual speech recognition](https://arxiv.org/pdf/1808.02480.pdf)
* [Contextual Speech Recognition with Difficult Negative Training Examples](https://arxiv.org/pdf/1810.12170.pdf)
* [Phoebe: Pronunciation-aware Contextualization for End-to-end Speech Recognition](https://www.bruguier.com/pub/phoebe.pdf)
* [Phoneme-Based Contextualization for Cross-Lingual Speech Recognition in End-to-End Models](https://arxiv.org/pdf/1906.09292.pdf)
* [Joint Grapheme and Phoneme Embeddings for Contextual End-to-End ASR](https://x-lance.sjtu.edu.cn/papers/2019/zhc00-chen-is2019.pdf)

### Contextual Transducer ("RNNTs")

* [Contextual RNN-T For Open Domain ASR](https://arxiv.org/pdf/2006.03411.pdf)
* [Multistate Encoding with End-To-End Speech RNN Transducer Network](https://ieeexplore.ieee.org/document/9054287)
* [Deep Shallow Fusion for RNN-T Personalization](https://arxiv.org/pdf/2011.07754.pdf)
* [Contextualized Streaming End-to-End Speech Recognition with Trie-Based Deep Biasing and Shallow Fusion](https://arxiv.org/pdf/2104.02194.pdf)
* [Context-Aware Transformer Transducer for Speech Recognition](https://arxiv.org/pdf/2111.03250.pdf)

### 2021

* [Tree-constrained Pointer Generator for End-to-end Contextual Speech Recognition](https://arxiv.org/abs/2109.00627)
* [Fast Contextual Adaptation with Neural Associative Memory for On-Device Personalized Speech Recognition](https://arxiv.org/pdf/2110.02220.pdf)

### 2022

* [Improving End-to-End Contextual Speech Recognition with Fine-grained Contextual Knowledge Selection](https://arxiv.org/pdf/2201.12806.pdf)
* [End-to-end contextual asr based on posterior distribution adaptation for hybrid ctc/attention system](https://arxiv.org/pdf/2202.09003.pdf)
* [Towards Contextual Spelling Correction for Customization of End-to-end Speech Recognition Systems](https://arxiv.org/pdf/2203.00888.pdf)

## External Contextualization
External modules such as Language Models, Error Correction models, and weighted FSTs applied to hypotheses of E2E ASR systems

### 2012

* [A Specialized WFST Approach for Class Models and Dynamic Vocabulary](https://www.isca-speech.org/archive_v0/archive_papers/interspeech_2012/i12_1075.pdf)

### 2015

* [Composition-based on-the-fly rescoring for salient n-gram biasing](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/43816.pdf)
* [Improved recognition of contact names in voice commands](https://ieeexplore.ieee.org/document/7178957)

### 2016

* [Personalized Speech recognition on mobile devices](https://arxiv.org/pdf/1603.03185.pdf&xid=17259,15700022,15700186,15700190,15700248.pdf)

### 2017

* [Keyword spotting for Google assistant using contextual speech recognition](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/be2559f953dce47e69f4d06692df1184719c4d4b.pdf)

### 2018

* [Contextual speech recognition in end-to-end neural network systems using beam search](https://www.isca-speech.org/archive_v0/Interspeech_2018/pdfs/2416.pdf)
* [Recurrent Neural Network Language Model Adaptation for Conversational Speech Recognition](https://www.danielpovey.com/files/2018_interspeech_lm_adapt.pdf)
* [End-to-end contextual speech recognition using class language models and a token passing decoder](https://arxiv.org/pdf/1812.02142.pdf)

### 2019

* [Contextual Recovery of Out-of-Lattice Named Entities in Automatic Speech Recognition](https://www.isca-speech.org/archive/pdfs/interspeech_2019/serrino19_interspeech.pdf)
* [Shallow-Fusion End-to-End Contextual Biasing](https://www.isca-speech.org/archive_v0/Interspeech_2019/pdfs/1209.pdf)
* [Personalization of End-to-End Speech Recognition on Mobile Devices for Named Entities](https://arxiv.org/pdf/1912.09251.pdf)


#### 2020

* [Joint Contextual Modeling for ASR Correction and Language Understanding](https://arxiv.org/pdf/2002.00750.pdf)
* [Bangla Voice Command Recognition in end-to-end System Using Topic Modeling based Contextual Rescoring](https://ieeexplore.ieee.org/document/9053970)
* [Fast and Robust Unsupervised Contextual Biasing for Speech Recognition](https://arxiv.org/pdf/2005.01677.pdf)
* [Contextualizing ASR Lattice Rescoring with Hybrid Pointer Network Language Model](https://arxiv.org/pdf/2005.07394.pdf)
* [Incorporating Written Domain Numeric Grammars into End-To-End Contextual Speech Recognition Systems for Improved Recognition of Numeric Sequences](https://ieeexplore.ieee.org/document/9054259)
* [Class LM and word mapping for contextual biasing in End-to-End ASR](https://arxiv.org/pdf/2007.05609.pdf)
* [Rapid RNN-T Adaptation Using Personalized Speech Synthesis and Neural Language Generator](https://www.microsoft.com/en-us/research/uploads/prod/2020/08/interspeech2020_RNNT_adapt_final-5f401f4f7a8e3.pdf)
* [Hierarchical Multi-Stage Word-to-Grapheme Named Entity Corrector for Automatic Speech Recognition](https://www.isca-speech.org/archive_v0/Interspeech_2020/pdfs/3174.pdf)
* [Improving accuracy of rare words for RNN-Transducer through unigram shallow fusion](https://arxiv.org/pdf/2012.00133.pdf)

### 2021

* [Domain-Aware Neural Language Models for Speech Recognition](https://arxiv.org/pdf/2101.03229.pdf)
* [Personalization Strategies for End-to-End Speech Recognition Systems](https://arxiv.org/pdf/2102.07739.pdf)
* [A Light-weight contextual spelling correction model for customizing transducer-based speech recognition systems](https://arxiv.org/pdf/2108.07493.pdf)
* [Spell my name: keyword boosted speech recognition](https://arxiv.org/pdf/2110.02791.pdf)
