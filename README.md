# DPNeT: Differentially Private Network Traffic Synthesis with Generative Adversarial Networks

Paper:
https://link.springer.com/chapter/10.1007/978-3-030-81242-3_1

Presentation:
https://drive.google.com/file/d/1CjjnNaoaXRqTy1SXb2Ft3jceG6eko5BS/view?usp=sharing

Abstract:
High quality network traffic data can be shared to enable knowledge discovery and advance cyber defense research. However, due to its sensitive nature, ensuring safe sharing of such data has always been a challenging problem. Current approaches for sharing networking data present several limitations to balance privacy (e.g., information leakage) and utility (e.g., availability and usefulness). To overcome those limitations, we develop DPNeT, a network traffic synthesis solution that generates high-quality network flows and satisfies (  ϵ ,   δ )-differential privacy. We adopt generative adversarial networks (GANs) to capture the characteristics of real network flows and a similarity-preserving embedding model for mixed-type attributes. Furthermore, we propose new techniques to improve the outcome of differentially private learning and provide the privacy analysis of the overall solution. Through a comprehensive evaluation with large-scale network flow data, we demonstrate that our solution is capable of producing realistic network flows.

This repository contains the all code necessary for training our DPNeT.

If this code is being used in your projects, please credit the paper:

@inproceedings{fan2021dpnet,
  title={DPNeT: Differentially Private Network Traffic Synthesis with Generative Adversarial Networks},
  author={Fan, Liyue and Pokkunuru, Akarsh},
  booktitle={IFIP Annual Conference on Data and Applications Security and Privacy},
  pages={3--21},
  year={2021},
  organization={Springer}
}
