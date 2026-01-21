## Overview

This repository provides an implementation of the Knowledge Distillation architecture and training procedure proposed in:

Mahouachi, R. *Knowledge distillation-driven commit-aware multimodal learning for software vulnerability detection*. Automated Software Engineering, 33, 48 (2026).

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

## Citation

If you use this repository in your research, please cite the following paper:

> Mahouachi, R. *Knowledge distillation-driven commit-aware multimodal learning for software vulnerability detection*. Automated Software Engineering, 33, 48 (2026). https://doi.org/10.1007/s10515-026-00595-z
