# Boosting Kidney Stone Identification in Endoscopic Images Using Two-Step Transfer Learning


This repository has the code to implement the methods described in the conference article: [*Boosting Kidney Stone Identification in Endoscopic Images Using Two-Step Transfer Learning*](https://arxiv.org/pdf/2210.13654), developed as part of the project [*"RECONDITE: Deep learning and image analysis methods for improving the endoscopic identification of kidney stones composition"*](https://www.researchgate.net/project/RECONDITE-Deep-learning-and-image-analysis-methods-for-improving-the-endoscopic-identification-of-kidney-stones-composition) at [Tecnologico de Monterrey](https://tec.mx/en) and [Université de Lorraine](http://www.univ-lorraine.fr). 



## Abstract
Knowing the cause of kidney stone formation is crucial to establish treatments that prevent recurrence. There are currently different approaches for determining the kidney stone type. However, the reference ex-vivo identification procedure can take up to several weeks, while an in-vivo visual recognition requires highly trained specialists. Machine learning models have been developed to provide urologists with an automated classification of kidney stones during an ureteroscopy; however, there is a general lack in terms of quality of the training data and methods. In this work, a two-step transfer learning approach is used to train the kidney stone classifier. The proposed approach transfers knowledge learned on a set of images of kidney stones acquired with a CCD camera (ex-vivo dataset) to a final model that classifies images from endoscopic images (ex-vivo dataset). The results show that learning features from different domains with similar information helps to improve the performance of a model that performs classification in real conditions (for instance, uncontrolled lighting conditions and blur). Finally, in comparison to models that are trained from scratch or by initializing ImageNet weights, the obtained results suggest that the two-step approach extracts features improving the identification of kidney stones in endoscopic images.

[[ArXiv]](https://arxiv.org/pdf/2210.13654)




---

## Contents

 
## Organization

No additional content directories are declared. 


## Contributors

Code for algorithms, applications and tools contributed by:

[Francisco Lopez-Tiro](https://scholar.google.es/citations?user=IlG06bYAAAAJ&hl=es), Juan Pablo Betancur-Rengifo

Please email us your comments, criticism, and questions at [`gilberto.ochoa@tec.mx`](mailto:gilberto.ochoa@tec.mx?subject=[GitHub]%20ks-baseline%20repository)


## Reference

If you use functions from this script in your work, please use the BibTex entry below for citation.

[[ArXiv]](https://arxiv.org/pdf/2210.13654) [[Paper]]([https://arxiv.org/pdf/2210.13654](https://link.springer.com/chapter/10.1007/978-3-031-47640-2_11))

```
@inproceedings{lopez2023boosting,
  title={Boosting kidney stone identification in endoscopic images using two-step transfer learning},
  author={Lopez-Tiro, Francisco and Flores-Araiza, Daniel and Betancur-Rengifo, Juan Pablo and Reyes-Amezcua, Ivan and Hubert, Jacques and Ochoa-Ruiz, Gilberto and Daul, Christian},
  booktitle={Mexican International Conference on Artificial Intelligence},
  pages={131--141},
  year={2023},
  organization={Springer}
}
```
