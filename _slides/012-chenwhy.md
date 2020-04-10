---
name: chenwhy
notes: ""
slidenum: 12
---
# Why is my classifier discriminatory?
[paper](https://papers.nips.cc/paper/7613-why-is-my-classifier-discriminatory.pdf)
Synopsis other design choices drive perceived bias:
- sample size
- features
- sampling distribution
main prediction: majority voting over multiple datasets
optimal prediction: bayes optimal
per dataset prediction: prediction on a single dataset
bias: loss incurred by the main prediction relative to the optimal prediction.
variance: average loss incurred by the predictions learned from different datasets relative to
the main prediction
noise: the remaining loss independent of the learning algorithm, often known as the Bayes error
recommendations:
1. get more samples
2. measure more variables