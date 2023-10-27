# NOTE: This is the anonymized version of another repository. It is intended for demonstration purposes only.

# anonymized-tokenizer

Train, evaluate and analyze BPE tokenizers.

<a href='https://github.com/abcde17/anonymized-tokenizer/actions/workflows/python-package.yml'><img src='https://github.com/abcde17/anonymized-tokenizer/actions/workflows/python-package.yml/badge.svg' alt='CI' /></a>
<a href='https://coveralls.io/github/abcde17/anonymized-tokenizer?branch=development'><img src='https://coveralls.io/repos/github/abcde17/anonymized-tokenizer/badge.svg?branch=development' alt='Coverage Status' /></a>
<a href="https://github.com/psf/black"><img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>

## Resources

* source code: [https://github.com/abcde17/anonymized-tokenizer](https://github.com/abcde17/anonymized-tokenizer)
* documentation: [https://abcde17.github.io/anonymized-tokenizer](https://abcde17.github.io/anonymized-tokenizer)

## Installation

``` bash
git clone https://github.com/abcde17/anonymized-tokenizer.git
pip install -r requirements.txt
```

-----------
## About

This repository provides easy-to-use tools to sample (weighted) data and subsequently train, evaluate and analyze a tokenizer.

<div align="center">
<img alt="sampling" src="docs/docs/images/filter-solid-margin.png" height="53">&nbsp;
&nbsp;
&nbsp;
&nbsp;
<img alt="training" src="docs/docs/images/brain-solid-margin.png" height="53">&nbsp;
&nbsp;
&nbsp;
&nbsp;
<img alt="evaluation" src="docs/docs/images/ruler-solid-margin.png" height="53">&nbsp;
&nbsp;
&nbsp;
&nbsp;
<img alt="analysis" src="docs/docs/images/magnifying-glass-solid-margin.png" height="53">&nbsp;
</div>
<div align="center">
<div align="center">
Sampling &nbsp;&nbsp;&nbsp;&nbsp;
Training &nbsp;&nbsp;&nbsp;
Evaluation &nbsp;&nbsp;
Analysis &nbsp;&nbsp;
</div>
&nbsp;
</div>

## Features

<img src="docs/docs/images/filter-solid-margin.png" height="13">&nbsp;&nbsp;Sampling

- customizable amount of (disjoint) sampled data for training and evaluation
- weighting of different categories and languages

<img src="docs/docs/images/brain-solid-margin.png" height="13">&nbsp;&nbsp;Training

- support for SentencePiece and HuggingFace
- customizable tokenizer features (vocabulary size, handling of whitespace and numbers, ..)

<img src="docs/docs/images/ruler-solid-margin.png" height="13">&nbsp;&nbsp;Evaluation

- computation of common tokenizer metrics (unknown rate, fertility, proportion of continued words, ..)

<img src="docs/docs/images/magnifying-glass-solid-margin.png" height="13">&nbsp;&nbsp;Analysis

- example tokenization
- vocabulary overlap and performance comparison across languages
- effect of the vocabulary size

-----------
