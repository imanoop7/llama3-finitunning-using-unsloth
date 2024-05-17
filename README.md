# Llama3 Finetuning using UnSloth

Welcome to the Llama3 finetuning project using the UnSloth framework. This repository contains the resources and instructions needed to finetune the Llama3 model on the 'yahma/alpaca-cleaned' dataset.

## Overview

The Llama3 model is a variant of the Llama language models, known for their efficiency and performance. In this project, we use the 'unsloth/llama-3-8b-bnb-4bit' model, which is optimized for finetuning with the UnSloth framework.

## Requirements

- Python 3.8+
- PyTorch 1.8+
- Transformers 4.5+
- UnSloth Framework

## Dataset

The dataset used for finetuning is 'yahma/alpaca-cleaned', which is a preprocessed and cleaned version suitable for various NLP tasks.

## Model

The model being finetuned is 'unsloth/llama-3-8b-bnb-4bit', a 4-bit quantized version of the Llama3 model, making it faster and more efficient for finetuning.

## Notebook

`llama3_finetuning.ipynb` is a Jupyter notebook that provides a comprehensive guide to the finetuning process. It includes steps for setting up the environment, loading the dataset, finetuning the model, and evaluating the results.

## Setup

To begin finetuning the Llama3 model, follow these steps:

1. Clone the repository:
   ``` bash
   git clone https://github.com/imanoop7/llama3-finitunning-using-unsloth/.git
2. Install the required dependencies
3. Execute the finetuning notebook
   
## Usage

After finetuning, the Llama3 model can be utilized for a variety of NLP tasks, leveraging its improved performance on the 'yahma/alpaca-cleaned' dataset.

## Contributing

Contributions to this project are highly encouraged. If you have suggestions for improvements or encounter any issues, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- The creators of the Llama3 model.
- The UnSloth team for providing the framework that facilitates efficient finetuning.



