# Asynchronous SGD
This repository contains the code used for running Asynchronous SGD on a random quadratic problem. The random seed is fixed, but each specific run will experience its own delays, so the results may vary between different runs. By default, the code uses 40 asynchronous workers.

## Reference
The code was used by paper "Asynchronous SGD Beats Minibatch SGD Under Arbitrary Delays" presented at NeurIPS 2022 ([arxiv](https://arxiv.org/abs/2206.07638), [openreview](https://openreview.net/forum?id=4XP0ZuQKXmV)). The paper can be cited using the following bib entry:
```
@article{mishchenko2022asynchronous,
  title={Asynchronous {SGD} Beats Minibatch {SGD} Under Arbitrary Delays},
  author={Mishchenko, Konstantin and Bach, Francis and Even, Mathieu and Woodworth, Blake},
  journal={arXiv preprint arXiv:2206.07638},
  year={2022}
}
```
