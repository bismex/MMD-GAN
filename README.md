# MMD-GAN with Repulsive Loss Function
GAN: generative adversarial nets; MMD: maximum mean discrepancy; TF: TensorFlow

This repository contains codes for MMD-GAN and the repulsive loss proposed in the following paper:

Improving MMD-GAN Training with Repulsive Loss Function.  Under review as a conference paper at ICLR 2019. URL: https://openreview.net/forum?id=HygjqjR9Km.

## Repository structure
The codes here were written along with my learning of Python and GAN, so I apologise if you find them quite messy, out-of-date or informal. 

The respository mainly contains two folders:
1. DeepLearning/my_sngan/SNGan \
This class defines how the model is trained and evaluated. 

2. GeneralTools \
- graph_func contains functions/classes related to TF Optimizer, Session, Summary, checkpoint file as well as metrics for evaluating generative models.
- layer_func contains
