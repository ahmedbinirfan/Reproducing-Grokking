# Reproducing Grokking

Hey there! This Jupyter notebook dives into reproducing the "grokking" phenomenon from the paper ["OMNIGROK: GROKKING BEYOND ALGORITHMIC DATA"](https://arxiv.org/pdf/2210.01117) by Power et al. Grokking is that weird thing where a model memorizes the training data perfectly but takes forever to actually generalize to new stuff—until it suddenly does.

## What's Inside

- A quick intro to grokking and a summary of the key paper findings.
- Code to generate a modular addition dataset (mod 97, 50/50 train/test split).
- A simple MLP model trained with AdamW optimizer.
- An experiment showing grokking with weight decay (the magic ingredient).
- A modified run without weight decay to see what happens (spoiler: no grokking).
- Plots of accuracy and loss curves for both runs.
- Some thoughts on why it works (or doesn't) and how it matches the paper.



