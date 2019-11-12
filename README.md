# Review Conversational Reading Comprehension

## Problem to Solve
Given a history of QAs where questions are from the customers previous utterances and answers are spans in a review, and the current question, find answer spans from the review. As similar to SQuAD 2, we have no answer questions in both the current and history of utterances.  
The model is expected to handle real-world applications where potential customers can chat/ask questions and get answers from a large pool of customer reviews (one dialogue can have answers from multiple reviews).

## Environment
**My hard disk is broken and not able to recover the code and corpus. Any help on recovery is appreciated.**

## Dataset
The annotated dataset is from the reviews of SemEval 2016 Task 5 for laptop and restaurant domain.
It can be downloaded [here](https://drive.google.com/file/d/1qSTs7VkamBsxKN2iOAsK40zwAF5f1xo1/view?usp=sharing).


## Setup

There is also a similar task called [RRC](https://github.com/howardhsu/BERT-for-RRC-ABSA) without dialogue history based on the same reviews but different annotations.

## Setup
**My hard disk is broken and not able to recover the code and corpus. Any help on recovery is appreciated.**

## Citation
```
@article{xu2019review,
  title={Review Conversational Reading Comprehension},
  author={Xu, Hu and Liu, Bing and Shu, Lei and Yu, Philip S},
  journal={arXiv preprint arXiv:1902.00821},
  year={2019}
}
```
