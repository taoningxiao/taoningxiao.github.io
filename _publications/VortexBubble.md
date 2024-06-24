---
title: "A Vortex Particle-on-Mesh Method for Soap Film Simulation"
header: 
    teaser: 'images/VortexBubble-teaser.jpg'
collection: publications
permalink: /publication/VortexBubble
excerpt: '<b>Ningxiao Tao</b>, Liangwang Ruan, Yitong Deng, Bo Zhu, Bin Wang, Baoquan Chen'
date: 2024-08-01
venue: 'ACM Transactions on Graphics (SIGGRAPH 2024)'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://taoningxiao.github.io/files/VortexBubble.pdf'
citation: #'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

This paper introduces a novel physically-based vortex fluid model for films, aimed at accurately simulating cascading vortical structures on deforming thin films. Central to our approach is a novel mechanism decomposing the film’s tangential velocity into circulation and dilatation components. These components are then evolved using a hybrid particle-mesh method, enabling the effective reconstruction of three-dimensional tangential velocities and seamlessly integrating surfactant and thickness dynamics into a unified framework. By coupling with its normal component and surface-tension model, our method is particularly adept at depicting complex interactions between in-plane vortices and out-of-plane physical phenomena, such as gravity, surfactant dynamics, and solid boundary, leading to highly realistic simulations of complex thin-film dynamics, achieving an unprecedented level of vortical details and physical realism.

## Citation
```
@article{Tao2024,
author = {Tao, Ningxiao and Ruan, Liangwang and Deng, Yitong and Zhu, Bo and Wang, Bin and Chen, Baoquan},
title = {A Vortex Particle-on-Mesh Method for Soap Film Simulation},
year = {2024},
issue_date = {Auguest 2024},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
volume = {43},
number = {4},
url = {https://doi.org/10.1145/3658165},
doi = {10.1145/3658165},
journal = {ACM Trans. Graph.},
month = {aug},
articleno = {53},
numpages = {14},
}
```