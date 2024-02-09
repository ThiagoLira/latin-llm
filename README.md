## Suite for the creation of a Classical Latin LLM

In this repo you will find code to generate a synthetic Classical Latin language dataset with OpenAI APIs (using the ideas from the [TinyStories paper](https://arxiv.org/abs/2305.07759)).
Refer to the notebook `create_dataset_with_openai.ipynb` to see dataset creation code.


### Finetuning a model with Latin Data

The `latin_lora.yml` file contains the configuration for finetuning an LLM using the dataset created with this repo using [Axolot](https://github.com/OpenAccess-AI-Collective/axolotl)
