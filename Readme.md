# Introduction
![](flaxgpt_logo.png)

FlaxGPT is a simplistic Flax implementation of GPT (decoder-only transformer) model.
The code is minimum in a single notebook and therefore good for hacking and educational purposes.

# Usage
Open the main [flax_gpt](https://colab.sandbox.google.com/github/codescv/flax-gpt/blob/main/flax_gpt.ipynb) colab and start hacking.

# Feature Roadmap
- [x] Implement GPT model using flax
- [x] Load / Convert LLaMA2-7B checkpoint for prediction
- [ ] Implement K-V cache in prediction
- [ ] Pretraining (example)
- [ ] Finetuning (example)
- [ ] LoRA finetuning
- [ ] Quantization
- [ ] Distributed Training (TPUs)

# Tutorials
Here are some tutorials of how I implemented GPT from scratch.

- [GPT From Scratch Using Flax](https://colab.sandbox.google.com/github/codescv/flax-gpt/blob/main/tutorials/GPT_From_Scratch_Using_Flax.ipynb) explains how I created FlaxGPT, step by step.
- [GPT From Scrach Using Jax](https://colab.sandbox.google.com/github/codescv/flax-gpt/blob/main/tutorials/GPT_From_Scratch_Using_Jax.ipynb) if you prefer a more "hardcore" implementation using only the low level jax, please check this out.
