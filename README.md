# Awesome Contextualization of E2E ASR [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)]  [![Contribution](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/stevenhillis/awesome-asr-contextualization/blob/main/CONTRIBUTING.md)

## Table of contents

* [Overview](#Overview)
* [Publications](#Publications)
  * [Deep Contextualization](#Deep-Contextualization)
    * [Contextual LAS](#Contextual-LAS-(CLAS))
    * [Contextual Transducer](#Contextual-Transducer-("RNNTs"))
    * [2021](#2021)
  * [External Contextualization](#External-Contextualization)

## Overview

This is a curated list of awesome papers on Contextualization of E2E ASR. <!--, paired with a short description of the primary contribution. -->

The purpose of contextualizating ASR outputs is to bias the results towards tokens, generally proper nouns or rare words, which are thought likely to be produced given the context of an audio signal. Correct transcription of these tokens might have an outsized impact on the value of the output, and incorrect transcription might otherwise be likely.

To add items to this page, open up a pull request. ([contributing guide](CONTRIBUTING.md))

## Publications

### Deep Contextualization
End to end approaches, integrated neural modules

#### Contextual LAS (CLAS)

* [Deep context: end-to-end contextual speech recognition](https://arxiv.org/pdf/1808.02480.pdf)
* [Contextual Speech Recognition with Difficult Negative Training Examples](https://arxiv.org/pdf/1810.12170.pdf)
* [Phoebe: Pronunciation-aware Contextualization for End-to-end Speech Recognition](https://www.bruguier.com/pub/phoebe.pdf)
* [Joint Grapheme and Phoneme Embeddings for Contextual End-to-End ASR](https://x-lance.sjtu.edu.cn/papers/2019/zhc00-chen-is2019.pdf)

#### Contextual Transducer ("RNNTs")

* [Contextual RNN-T For Open Domain ASR](https://arxiv.org/pdf/2006.03411.pdf)
* [Deep Shallow Fusion for RNN-T Personalization](https://arxiv.org/pdf/2011.07754.pdf)
* [Contextualized Streaming End-to-End Speech Recognition with Trie-Based Deep Biasing and Shallow Fusion](https://arxiv.org/pdf/2104.02194.pdf)

#### 2021

* [Tree-constrained Pointer Generator for End-to-end Contextual Speech Recognition](https://arxiv.org/abs/2109.00627)
* [Fast Contextual Adaptation with Neural Associative Memory for On-Device Personalized Speech Recognition](https://arxiv.org/pdf/2110.02220.pdf)

### External Contextualization
External modules such as Language Models, Error Correction models, and weighted FSTs applied to hypotheses of E2E ASR system
