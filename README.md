# PEFT Visualization Demo

`fine_tuning_on_regression_tasks.ipynb` provides animated visualizations of fine-tuning methods on simple regression tasks. It covers:

- Standard fine-tuning (all parameters)
- Low-Rank Adaptation (LoRA) (with and without merging)
- Weight-Decomposed Low Rank Adaptation (DoRA)

[View the notebook with nbsanity](https://nbsanity.com/gsganden/peft_demo/blob/main/fine_tuning_on_regression_tasks.ipynb) to see the animations in a web browser.


## Acknowledgments

- LoRA and DoRA implementations adapted from [Improving LoRA: Implementing Weight-Decomposed Low-Rank Adaptation (DoRA) from Scratch](https://magazine.sebastianraschka.com/p/lora-and-dora-from-scratch).
- Visualization methods adapted from [FastAI v3 Lesson 2: SGD](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-sgd.ipynb).
