# Learning-to-Move-with-Style-Few-Shot-Cross-Modal-Style-Transfer-for-Creative-Robot-Motion-Generation
This repository contains the implementation code for paper: <br>
__Learning to Move with Style: Few-Shot Cross-Modal Style Transfer for Creative Robot Motion Generation__ <br>
Kieran Woodward, Alicia Falcon Caro and Steve Benford <br>
_39th Conference on Neural Information Processing Systems (NeurIPS), 2025_ <br>

If you find this code or idea useful, please consider citing our work:
```bib
@inproceedings{yang2020rethinking,
  title={Rethinking the Value of Labels for Improving Class-Imbalanced Learning},
  author={Woodward, Kieran, Falcon-Caro, Alicia and Benford, Steve},
  booktitle={Conference on Neural Information Processing Systems (NeurIPS)},
  year={2025}
}
```


## Abstract
As robots increasingly participate in creative and social contexts, the ability to generate creative, stylised movements becomes crucial for applications ranging from performance art to human-robot collaboration. We present a novel framework for cross-modal style transfer that enables robots to learn new movement styles by adapting existing human-robot dance collaborations using human movement videos. Our dual-stream architecture processes raw video frames and pose sequences through cross-modal attention mechanisms, capturing rhythm, acceleration patterns, and spatial coordination characteristics of different movement styles. The transformer-based style transfer network generates motion transformations through residual learning while preserving the trajectory of original dance movements, enabling few-shot adaptation using only 3-6 demonstration videos. We evaluate across ballet, jazz, flamenco, contemporary dance and martial arts, introducing a creativity parameter that provides control over the style-trajectory trade-off. Results demonstrate successful style differentiation with overall style transfer scores increasing 6.7x to 7.4x from minimum to maximum creativity settings, advancing human-robot creative collaboration by expanding robots' expressive vocabulary beyond their original choreographic context.

