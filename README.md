# SDD Deep learning project

This is a school project for the SDD course at ISAE. Its aim is to build a Small Language Model (SLM), and to train it on a generic dataset. Then, measure the importance and impact of the repetition of tokens over training.

The paper over which this is based can be found here : https://arxiv.org/abs/2305.16264.


## Installation

This code runs on Python 3, and requires the following library :

- numpy
- plotly
- pandas
- matplotlib
- torch
- datasets
- tiktoken
- tqdm

To install each library, replace the stars by the library name and run this inside a pip virtual environnment :

```bash
pip install *****
```

## Usage

To start a training, use the SLM.ipynb notebook. It will save the result in a dedicated folder (automatically created) during and after training, including a csv of the loss and a text description of the training. A training as displayed in the video lasts 2h on a dedicated GPU.


The results produced can then be loaded using Compare_solutions.ipynb notebook, to produce graph and analysis.


The Training_Results folder contains some models description and training results.

