## Overview

This repository contains the implementation of the Knowledge Distillation (KD) framework proposed in the paper : “Knowledge Distillation-Driven Commit-Aware Multimodal Learning for Software Vulnerability Detection”.

It includes the model architecture, training pipeline, and distillation strategy used to transfer knowledge from a teacher model to a lightweight student model. The code focuses on the core methodological components of the approach.

Dataset preprocessing and experimental settings are fully described in the paper.

## Datasets

This work uses publicly available vulnerability detection datasets.  
The datasets themselves are not included in this repository.

- **DiverseVul**  
  Chen, Y., Ding, Z., Alowain, L., Chen, X., & Wagner, D. (2023).  
  *DiverseVul: A New Vulnerable Source Code Dataset for Deep Learning–Based Vulnerability Detection.*  
  Proceedings of the 26th International Symposium on Research in Attacks, Intrusions and Defenses (RAID 2023).  
  Dataset: https://github.com/wagner-group/diversevul

- **Devign**  
  Zhou, Y., Liu, S., Siow, J., Du, X., & Liu, Y. (2019).  
  *Devign: Effective Vulnerability Identification by Learning Comprehensive Program Semantics via Graph Neural Networks.*  
  Advances in Neural Information Processing Systems (NeurIPS), 32.  
  Dataset: https://github.com/epicosy/devign
