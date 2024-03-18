# INVICTA Spring School
## Training Spiking Neural Networks Using Lessons from Deep Learning

This repository contains the notebooks related to training
spiking neural networks presented at the INVICTA Spring School
(Porto, Portugal) for the workshop *Training Brain-Inspired Spiking Neural Networks using Lessons from Deep Learning* 
presented by [Jason Eshraghian](https:///ncg.ucsc.edu).

![Abstract](/static/hls4nm-flow-horizontal.png)

## Abstract

The brain is the perfect place to look for inspiration to develop more efficient neural networks. Our brains are constantly adapting, our neurons processing all that we know, mistakes we've made, failed predictions - all working to anticipate what will happen next with incredible speed. Our brains are also amazingly efficient. Training large-scale neural networks can cost more than millions of dollars in energy expense, yet the human brain does remarkably well on a power budget of 20 watts.

One of the main differences with modern deep learning is that the brain encodes and processes information as temporal spikes rather than continuous, high-precision activations. This presentation will dive into the intersection between neuroscience and deep learning. We will explore how spiking neurons and learning rules derived from neuroscience intersect with deep learning, and how the Python package Eshraghian developed - snnTorch - spans across the neuroscience, machine learning, and hardware abstractions to drive forward the next generation of deep learning algorithms.

## Tutorial

There are three tutorial components in this repo:

* One for modelling simple spiking neurons
* One for training spiking neural networks using [snnTorch](https://github.com/jeshraghian/snntorch)
* One for making them hardware-friendly using low-precision training

## Software

| Title                                                                                           | Colab Link                                                                                                                                  |
|-------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| Spiking Neurons from Scratch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeshraghian/invicta-spring-school/blob/main/notebooks/invicta_pt1.ipynb) |
| **Cheat-Sheet:** Spiking Neurons from Scratch | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeshraghian/invicta-spring-school/blob/main/notebooks/invicta-pt1-cheatsheet.ipynb) |
| Training Spiking Neural Networks with [snnTorch](https://github.com/jeshraghian/snntorch) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeshraghian/invicta-spring-school/blob/main/notebooks/invicta_pt2.ipynb) |
| **Cheat-Sheet:** Training Spiking Neural Networks with [snnTorch](https://github.com/jeshraghian/snntorch) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeshraghian/invicta-spring-school/blob/main/notebooks/invicta-pt2-cheatsheet.ipynb) |
| Low-Precision SNNs | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeshraghian/invicta-spring-school/blob/main/notebooks/invicta-pt3.ipynb) |
| **Cheat-Sheet:** Low-Precision SNNs | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jeshraghian/invicta-spring-school/blob/main/notebooks/invicta-pt3-cheatsheet.ipynb) |

## Speaker

### Jason Eshraghian, Assistant Professor, UC Santa Cruz

<img src="static/jason_eshraghian.jpg" width=300px alt="Jason Eshraghian">

Jason K. Eshraghian received the B.Eng. (electrical and electronic), L.L.B., and
Ph.D. degrees from The University of Western Australia, Perth, WA, Australia, in
2016 and 2019, respectively. From 2019 to 2022, he was a Post-Doctoral Research
Fellow at the University of Michigan, Ann Arbor MI, USA. He is currently an
Assistant Professor with the Department of Electrical and Computer Engineering,
The University of California at Santa Cruz, Santa Cruz, CA, USA. His research
interests include neuromorphic computing, resistive random access memory (RRAM)
circuits, and spiking neural networks.
