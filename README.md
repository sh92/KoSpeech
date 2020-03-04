# Korean-Speech-Recognition  

![build](https://img.shields.io/badge/build-Passing-83b6fa) ![license](https://img.shields.io/badge/license-Apache--2.0-cba5b6) ![language](https://img.shields.io/badge/version-Python--3.7-8ea5b6) ![framework](https://img.shields.io/badge/framework-PyTorch-729afa) ![team](https://img.shields.io/badge/Team-Kai.Lib-ab6d7b)     
  
### [**Documentation**](https://sh951011.github.io/Korean-Speech-Recognition/)  

# Introduction

This is project for Korean Speech Recognition using LAS (Listen, Attend and Spell) models   
implemented in [PyTorch](http://pytorch.org).  
We appreciate any kind of feedback or contribution.

## Roadmap
  
Speech recognition is an interdisciplinary subfield of computational linguistics that develops methodologies and technologies that enables the recognition and translation of spoken language into text by computers.  
  
We mainly referred to following papers.  
  
 [「Listen, Attend and Spell」](https://arxiv.org/abs/1508.01211)  
   
[「SpecAugment: A Simple Data Augmentation Method for Automatic Speech Recognition」](https://arxiv.org/abs/1904.08779).   
  
if you want to study the feature of audio, we recommend this papers.  
  
[「Voice Recognition Using MFCC Algirithm」](https://pdfs.semanticscholar.org/32d7/2b00454d5155599fb9e8e5119e16970db50d.pdf).  
  
Our project based on Seq2seq with Attention Architecture.  

Seq2seq is a fast evolving field with new techniques and architectures being published frequently.  
  
[More details](https://github.com/sh951011/Korean-Speech-Recognition/wiki/More-Details)

## Installation
This package requires Python 3.5.   
We recommend creating a new virtual environment for this project (using virtualenv or conda).  

### Prerequisites
  
* Numpy: `pip install numpy` (Refer [here](https://github.com/numpy/numpy) for problem installing Numpy).
* PyTorch: Refer to [PyTorch website](http://pytorch.org/) to install the version w.r.t. your environment.
* Pandas: `pip install pandas` (Refer [here](https://github.com/pandas-dev/pandas) for problem installing Pandas)  
* librosa: `pip install librosa` (Refer [here](https://github.com/librosa/librosa) for problem installing librosa)
* tqdm: `pip install tqdm` (Refer [here](https://github.com/tqdm/tqdm) for problem installing tqdm)  
  
## Get Started
### Preparation before Training

Refer [here](https://sh951011.github.io/Korean-Speech-Recognition/notes/Preparation.html) before Training.  
The above document is written in Korean.  
We will also write a document in English as soon as possible, so please wait a little bit.  
  
If you already have another dataset, please modify the data set path to [define.py](https://github.com/sh951011/Korean-Speech-Recognition/blob/master/utils/define.py) as appropriate.  

### Train and Test
if you want to start training, you should run [main.py](https://github.com/sh951011/Korean-Speech-Recognition/blob/master/main.py).    
or after training, you want to start testing, you should run [test.py](https://github.com/sh951011/Korean-Speech-Recognition/blob/master/test.py).  
  
you can set up a hyperparameters [hparams.py](https://github.com/sh951011/Korean-Speech-Recognition/blob/master/utils/hparams.py).  
An explanation of hparams is [here](https://sh951011.github.io/Korean-Speech-Recognition/Hparams.html).  
  

## Troubleshoots and Contributing
If you have any questions, bug reports, and feature requests, please [open an issue](https://github.com/sh951011/Korean-Speech-Recognition/issues) on Github.  
or Contacts sh951011@gmail.com please.
  
We appreciate any kind of feedback or contribution.  Feel free to proceed with small issues like bug fixes, documentation improvement.  For major contributions and new features, please discuss with the collaborators in corresponding issues.  

### Code Style
We follow [Google Python Style Guide](https://google.github.io/styleguide/pyguide.html) for code style.  Especially the style of docstrings is important to generate documentation.
  
## Reference   
  
### Paper
[[1] 「Listen, Attend and Spell」  Paper](https://arxiv.org/abs/1508.01211)   
[[2] 「Attention-Based Models for Speech Recognition」  Paper](https://arxiv.org/pdf/1506.07503.pdf)   
[[3] 「A Structured Self-attentive Sentence Embedding」 Paper](https://arxiv.org/abs/1703.03130)  
[[4] 「A Simple Data Augmentation Method for Automatic Speech Recognition」  Paper](https://arxiv.org/abs/1904.08779)     
[[5] 「Voice Recognition Using MFCC Algorithm」  Paper](https://pdfs.semanticscholar.org/32d7/2b00454d5155599fb9e8e5119e16970db50d.pdf)     
[[6] 「Deep Speech: Scaling up end-to-End Speech Recognition」  Paper](https://arxiv.org/abs/1412.5567)    
[[7] 「Deep Speech 2: End-to-End Speech Recognition in English and Mandarin」  Paper](https://arxiv.org/abs/1512.02595)    

### Code  
  
[[1]   IBM pytorch-seq2seq](https://github.com/IBM/pytorch-seq2seq)   
[[2]   PyTorch Spec-Augmentation](https://github.com/DemisEom/SpecAugment/blob/master/SpecAugment/spec_augment_pytorch.py)     
[[3]   PyTorch-VGG Net](https://github.com/chengyangfu/pytorch-vgg-cifar10/blob/master/vgg.py)  
  
### else
[[1]   A.I Hub Korean Voice Dataset](http://www.aihub.or.kr/aidata/105)   
[[2]   Levenshtein Distance](https://en.wikipedia.org/wiki/Levenshtein_distance)      
[[3]   Documentation](https://sh951011.github.io/Korean-Speech-Recognition/)   
  
## License
```
Copyright (c) 2020 Kai.Lib

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
