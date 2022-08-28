---
title: "Point Cloud Generation with Continuous Conditioning"
collection: publications
permalink: /publication/2022-03-30-triess2022aistats
excerpt: 'This paper proposes a novel generative adversarial network (GAN) setup that generates 3D point cloud shapes conditioned on a continuous parameter.'
date: 2022-03-30
venue: 'International Conference on Artificial Intelligence and Statistics (AISTATS)'
paperurl: 'https://arxiv.org/abs/2202.08526'
citation:
---
[[pdf](https://arxiv.org/pdf/2202.08526.pdf)]
[[project](https://larissa.triess.eu/continuous-generation)]

Generative models can be used to synthesize 3D objects of high quality and diversity.
However, there is typically no control over the properties of the generated object.
This paper proposes a novel generative adversarial network (GAN) setup that generates 3D point cloud shapes conditioned on a continuous parameter.
In an exemplary application, we use this to guide the generative process to create a 3D object with a custom-fit shape.
We formulate this generation process in a multi-task setting by using the concept of auxiliary classifier GANs.
Further, we propose to sample the generator label input for training from a kernel density estimation (KDE) of the dataset.
Our ablations show that this leads to significant performance increase in regions with few samples.
Extensive quantitative and qualitative experiments show that we gain explicit control over the object dimensions while maintaining good generation quality and diversity.

Recommended citation:
```bibtex
@inproceedings{triess2022aistats,
    title = {Point Cloud Generation with Continuous Conditioning},
    author = {Triess, Larissa T. and B\"uhler, Andre and Peter, David and Flohr, Fabian B. and Z\"ollner, Marius},
    booktitle = {Proc. International Conference on Artificial Intelligence and Statistics (AISTATS)},
    pages = {4462--4481},
    year = {2022},
}
```
