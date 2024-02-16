Code I wrote as part of the CMU 10701 Final Project. The task was to train a French to English machine translation model on a Kaggle dataset (https://www.kaggle.com/datasets/dhruvildave/en-fr-translation-dataset/) using multiple approaches. My contributions contained two parts:

1. Implementation of a transformer model (model_Transformer.py). In addition, I implemented an automatic differentiation-driven hyperparameter optimization (from https://arxiv.org/abs/1909.13371) and tested the effects of starting with different initial conditions on train and test loss (transformer_hyperopt_test.py).

2. Finetuning of llama-2-7b (from https://github.com/facebookresearch/llama) via adapter.
