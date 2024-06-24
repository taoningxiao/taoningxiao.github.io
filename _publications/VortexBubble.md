---
title: "A Vortex Particle-on-Mesh Method for Soap Film Simulation"
collection: publications
permalink: /publication/VortexBubble
excerpt: #'This paper is about the number 1. The number 2 is left for future work.'
date: #2024-07-29
venue: 'Siggraph 2024'
slidesurl: #'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/VortexBubble.pdf'
citation: '@article{Tao2024,
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
}'
---

This paper introduces a novel physically-based vortex fluid model for films, aimed at accurately simulating cascading vortical structures on deforming thin films. Central to our approach is a novel mechanism decomposing the film’s tangential velocity into circulation and dilatation components. These components are then evolved using a hybrid particle-mesh method, enabling the effective reconstruction of three-dimensional tangential velocities and seamlessly integrating surfactant and thickness dynamics into a unified framework. By coupling with its normal component and surface-tension model, our method is particularly adept at depicting complex interactions between in-plane vortices and out-of-plane physical phenomena, such as gravity, surfactant dynamics, and solid boundary, leading to highly realistic simulations of complex thin-film dynamics, achieving an unprecedented level of vortical details and physical realism.