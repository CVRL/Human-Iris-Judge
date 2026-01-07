# Human Iris Judge #
Official GitHub repository for the paper: Mahsa Mitcheff and Adam Czajka, "When Humans Judge Irises: Pupil Size Normalization as an Aid and Synthetic Irises as a Challenge," IEEE Workshop on Manipulation, Generative, Adversarial and Presentation Attacks In Biometrics (MGA-PAD), Tucson, AZ, March 7, 2026 **([ArXiv](xxx) | [IEEEXplore](xxx))**


![synthetic_samples](https://github.com/CVRL/Human-Iris-Judge/assets/synthetic_samples.png)


### Table of contents
* [Abstract](#abstract)
* [Dataset of Human Judgements](#dataset)
* [Citation](#citation)

<a name="abstract"/></a>
### Abstract

Iris recognition is a mature biometric technology offering remarkable precision and speed, and allowing for large-scale deployments to populations exceeding a billion enrolled users (e.g., AADHAAR in India). However, in forensic applications, a human expert may be needed to review and confirm a positive identification before an iris matching result can be presented as evidence in court, especially in cases where processed samples are degraded (e.g., in post-mortem cases) or where there is a need to judge whether the sample is authentic, rather than a result of a presentation attack. 

This paper presents a study that examines human performance in iris verification in two controlled scenarios: (a) under varying pupil sizes, with and without a linear/nonlinear alignment of the pupil size between compared images, and (b) when both genuine and impostor iris image pairs are synthetically generated. The results demonstrate that pupil size normalization carried out by a modern autoencoder-based identity-preserving image-to-image translation model significantly improves verification accuracy. Participants were also able to determine whether iris pairs corresponded to the same or different eyes when both images were either authentic or synthetic. However, accuracy declined when subjects were comparing authentic irises against high-quality, same-eye synthetic counterparts. These findings (a) demonstrate the importance of pupil-size alignment for iris matching tasks in which humans are involved, and (b) indicate that despite the high fidelity of modern generative models, same-eye synthetic iris images are more often judged by humans as different-eye images, compared to same-eye authentic image pairs. 

<a name="dataset"/></a>
### Dataset of Human Judgements

(to be added before the Workshop presentation in March 2026)

<a name="citation"/></a>
### Citation

If you find this work useful in your research, please cite the following paper:

```
@inproceedings{mitcheff2024privacysafeirispresentationattack,
      title={When Humans Judge Irises: Pupil Size Normalization as an Aid and Synthetic Irises as a Challenge}, 
      author={Mahsa Mitcheff and Adam Czajka},
      year={2026},
      booktitle={IEEE WACV Workshop on Manipulation, Generative, Adversarial and Presentation Attacks In Biometrics (MGA-PAD), Tucson, AZ},
}
```
