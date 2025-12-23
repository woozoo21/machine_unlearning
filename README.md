# Machine Unlearning via Gradient Ascent
**By Joshua Sojan, Tyler Ham, Sashreek Rewatkar**
This repository contains the code and research paper for studying machine unlearning
as an approximation to full retraining.

## Overview
As AI datasets grow and more user data is trained on, 
there is an ever growing concern for data privacy and training on sensitive data. 
We evaluate whether gradient-ascent unlearning can match the accuracy of retraining
while reducing computational cost. Experiments are conducted on the AG News dataset
using a Transformer based classifier.

## Code
All experiments were run in a single Google Colab notebook:
- `NN_unlearning.ipynb`

The notebook includes:
- Control training
- Retraining after data removal
- Gradient-ascent unlearning
- Accuracy, MSE, and runtime evaluation

## Paper
The accompanying research paper (`Unlearning Research Paper - Josh, Tyler, Sashreek.pdf`) is written in NeurIPS format and
documents the methodology and results.

## Dataset
AG News dataset from HuggingFace:
https://huggingface.co/datasets/ag_news

## Notes
This project was developed and executed in Google Colab using the NVIDIA A100 GPU.
