GraphGAN is a Generative Adversarial Network (GAN) variant specifically designed for graph data. It is a powerful framework that utilizes GANs to generate and manipulate graph structures. GraphGAN incorporates graph embeddings and graph convolutional networks (GCNs) to capture the structural characteristics of input graphs and generate new graph samples. By training the generator and discriminator networks in an adversarial manner, GraphGAN learns to generate realistic and diverse graph structures that preserve important features of the input data. This makes it particularly useful for applications involving graph data, such as social networks, molecular structures, and recommendation systems. GraphGAN offers a promising approach for graph generation, representation learning, and graph-based tasks, contributing to the advancement of machine learning and data analysis in graph domains.
For more detail:
[GraphGAN](https://github.com/hwwang55/GraphGAN)

### Requirements
The code has been tested running under Python 3.6.5, with the following packages installed (along with their dependencies):

- tensorflow == 1.8.0
- tqdm == 4.23.4 (for displaying the progress bar)
- numpy == 1.14.3
- sklearn == 0.19.1


```
  @inproceedings{wang2018graphgan,
  title={Graphgan: Graph representation learning with generative adversarial nets},
  author={Wang, Hongwei and Wang, Jia and Wang, Jialin and Zhao, Miao and Zhang, Weinan and Zhang, Fuzheng and Xie, Xing and Guo, Minyi},
  booktitle={Proceedings of the AAAI conference on artificial intelligence},
  volume={32},
  number={1},
  year={2018}}
```
