
# <div align="center">HawkRAG: Bridge Long Context and Complex Tasks via Global-Aware Retrieval<div>

<div align="center">
<a href="https://arxiv.org/" target="_blank"><img src=https://img.shields.io/badge/arXiv-b5212f.svg?logo=arxiv></a>
<a href="https://huggingface.co/datasets/" target="_blank"><img src=https://img.shields.io/badge/%F0%9F%A4%97%20HuggingFace%20Datasets-27b3b4.svg></a>
<a href="https://github.com/"><img alt="License" src="https://img.shields.io/badge/LICENSE-MIT-green"></a>
<a><img alt="Static Badge" src="https://img.shields.io/badge/made_with-Python-blue"></a>
</div>

<h4 align="center">

<p>
<a href="#sparkles-features">Features</a> |
<a href="#running-quick-start">Quick-Start</a> |
<a href="#raised_hands-additional-faqs"> FAQs</a>
</p>



## Overview

**HawkRAG** is a novel method that extends Retrieval-Augmented Generation (RAG) by incorporating global awareness for long contexts, thus expanding the standard RAG framework to a broader scope of applications. HawkRAG addresses the limitations of standard RAG, which struggles with complex queries requiring high-level information aggregation over long contexts. By efficiently perceiving long contexts and forming a compact yet comprehensive global memory, HawkRAG generates context-dependent clues that enable precise text retrieval and answer generation.



## Key Features

- **Global Memory Module**: HawkRAG integrates a memory module to maintain a global perspective, significantly improving the ability to handle long contexts.
- **Context-Dependent Clues**: Generates clues based on global memory, bridging the gap between the raw input context and the ground-truth answer.
- **Flexible Integration**: Can work with various generative models to produce accurate and detailed answers from complex queries.

## Examples
<p align="center">
<img src="asset/case.jpg">
</p>

## HawkRAG Demo
<div style="display: flex; justify-content: space-around;">
  <div style="text-align: center;">
    <img src="./asset/demo.gif" style="width: 100%;">
  </div>
</div>


## Quick-Start

### Evaluation

To evaluate HawkRAG on different benchmarks, run the following scripts:

```bash
bash scripts/eval_longbench.sh
bash scripts/eval_infinitebench.sh
bash scripts/eval_domainbench.sh
```

### Training

To train the memory model used in HawkRAG, use the following script:

```bash
bash scripts/train_memory_model.sh
```

## Citation

If you use HawkRAG in your research, please cite our paper:

```bibtex
@article{hawkRAG2024,
  title={HawkRAG: Bridge Long Context and Complex Tasks via Global-Aware Retrieval},
  author={Hongjin Qian, Peitian Zhang, Zheng Liu, Kelong Mao and Zhicheng Dou},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2024}
}
```






