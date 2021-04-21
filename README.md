# Speech2text & Denoise

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/ml_pathogen_identification_ner/blob/master/LICENSE)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![scikit-learn 0.23.2](https://img.shields.io/badge/scikit_learn-0.23.2-blue)](https://scikit-learn.org/stable/)
[![torch 0.23.2](https://img.shields.io/badge/torch-1.8.1-blue)](https://pytorch.org/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)

## Description
Speech to text & Denoiser using Wav2Vec pretrained model.
Denoiser using Dual-signal Transformation LSTM Network.
Fine-Tune Wav2Vec2 model 

We follow the next steps:
1. Data preparation
2. Data preprocessing
3. Modeling with Wav2Vec2 model
4. Modeling after denoise
5. Fine-tune Wav2Vec multi-language ASR 

From Wec2Vec2_Denoise.ipynb:
| Levenshtein metrics | Mean | Median |
|---|---|---|
| Word Error Rate | 0.26 | 0.20 |
| Match Error Rate | 0.25 | 0.2 |
| Word Information Lost | 0.40 | 0.36 |

