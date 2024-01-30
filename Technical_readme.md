# BERTNN: Technical Documentation

## Introduction

This document serves as the technical README for BERTNN, a tool for predicting affective meanings using contextual embeddings. It's intended for users with a background in machine learning and natural language processing, who are interested in the technicalities of the BERTNN model.

## Conceptual Framework

BERTNN is built on the premise of leveraging the BERT (Bidirectional Encoder Representations from Transformers) model for sentiment analysis and emotional linguistics within a sociological context. The model's core functionality is to estimate Evaluation, Potency, and Activity (EPA) values of words in varying contexts, guided by MABMO grammar.

## Model Details

### Base Model

- **BERT Architecture**: BERTNN utilizes the transformer architecture from Hugging Face's Transformers library. The model is fine-tuned for the specific task of extracting affective meanings from text.

## Implementation

BERTNN's implementation involves several key components:

1. **Contextual Analysis**: The model considers the context in which words are used to accurately estimate their affective meanings.
2. **EPA Value Estimation**: Using BERT's deep learning capabilities, BERTNN estimates the EPA values for words in different roles (identity, behavior, modifier) within an event.

For researchers and practitioners, BERTNN offers several advanced features:

- **Custom Event Analysis**: Ability to analyze custom events crafted in MABMO grammar.

## Contributing

Contributions to BERTNN are welcome. Please adhere to the project's contribution guidelines for submitting pull requests or issues.


## Citation

If you use BERTNN in your research, please cite:

> Mostafavi, M., Porter, M. D., & Robinson, D. T. (2024). Contextual Embeddings in Sociological Research: Expanding the Analysis of Sentiment and Social Dynamics. *[To be published ib] Sociological Methodology Journal*.

---

**Disclaimer**: The BERTNN project is subject to ongoing development and improvements. The methods and data described in this documentation are liable to change.
