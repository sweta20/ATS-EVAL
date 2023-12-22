# ATS-EVAL

This repository contains the code for our upcoming TACL paper: [Do Text Simplification Systems Preserve Meaning? A Human Evaluation via Reading Comprehension](https://arxiv.org/abs/2312.10126).

## Abstract

Automatic text simplification (TS) aims to automate the process of rewriting text to make it easier for people to read. A prerequisite for TS to be useful is that it should convey information that is consistent with the meaning of the original text. However, current TS evaluation protocols assess system outputs for simplicity and meaning preservation without regard for the document context in which output sentences occur and for how people understand them. In this work, we introduce a human evaluation framework to assess whether simplified texts preserve meaning using reading comprehension questions.  With this framework, we conduct a thorough human evaluation of texts by humans and by nine automatic systems. Supervised systems that leverage pre-training knowledge achieve the highest scores on the reading comprehension (RC) tasks amongst the automatic controllable TS systems. However, even the best-performing supervised system struggles with at least 14% of the questions, marking them as "unanswerable" based on simplified content. We further investigate how existing TS evaluation metrics and automatic question-answering systems approximate the human judgments we obtained. 

## Data and Code

All the collected annotations are released in the file [all-ann-final-model-paper.csv](https://github.com/sweta20/ATS-EVAL/blob/main/all-ann-final-model-paper.csv) and the analysis presented in the paper can be reproduced via the [shared colab](https://colab.research.google.com/drive/1EpnOiQACaHyBBLIJSu2kWtrAVtPXFpk3?usp=sharing) or the [notebook](https://github.com/sweta20/ATS-EVAL/blob/main/All_Analysis.ipynb).

## Citation
```
@article{agrawal2023text,
  title={Do Text Simplification Systems Preserve Meaning? A Human Evaluation via Reading Comprehension},
  author={Agrawal, Sweta and Carpuat, Marine},
  journal={arXiv preprint arXiv:2312.10126},
  year={2023}
}
```
