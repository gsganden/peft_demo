# LoRA and DoRA Visualization Demo

This project demonstrates different parameter-efficient fine-tuning methods (LoRA and DoRA) on a simple regression task. It provides interactive visualizations of how these methods adapt pre-trained models to new tasks.

## Overview

`lora.ipynb` shows how different adaptation methods perform when transferring a model trained on one function (quadratic) to approximate another function (cubic). It includes:

- Standard fine-tuning (all parameters)
- Low-Rank Adaptation (LoRA)
- Low-Rank Adaptation with merging
- Weight-Decomposed Low Rank Adaptation (DoRA)

## License

MIT License - feel free to use and modify for your own projects.

## Acknowledgments

This implementation is inspired by:
- [Improving LoRA: Implementing Weight-Decomposed Low-Rank Adaptation (DoRA) from Scratch
](https://magazine.sebastianraschka.com/p/lora-and-dora-from-scratch)
- [FastAI v3 Lesson 2: SGD](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-sgd.ipynb)
