#  TCKD: Task-Oriented Contrastive Knowledge Distillation for Object Detection
After the paper is accepted, we will provide code for this paper.

## Abstract
Most existing prediction-based distillation methods for object detection suffer from misalignment between distillation losses and optimization objectives, which hinders the effective transfer of critical knowledge and severely limits the student’s improvement. To address this challenge, we propose a novel task oriented knowledge distillation (TCKD) method that transfers both classification and regression knowledge through two ef
ficient distillation losses: class-wise contrastive distillation loss (CCDL) for classification and point-wise contrastive distillation loss (PCDL) for regression. Specifically, CCDL constructs positive and negative samples based on inter-class predictions and establishes inter-class relationships by calculating the similarity between samples. This guides the model to effectively focus on regions where the objects align with their corresponding classes. PCDL generates positive and negative samples by leveraging sample points at different spatial positions, and captures finer grained localization differences through similarity computation. Moreover, the proposed foreground-focused strategy used for PCDL effectively reduces background noise and alleviates the distribution imbalance between the foreground and background. Extensive experiments on the MS COCO2017, visDrone2019, and TinyPerson benchmarks demonstrate that TCKD not only achieves superior performance on large-scale datasets and challenging small object datasets but is also adaptable to various detectors.

## Results
![image](https://github.com/D-ace11/TCKD/blob/main/fig1.png)
![image](https://github.com/D-ace11/TCKD/blob/main/fig2.png)
![image](https://github.com/D-ace11/TCKD/blob/main/fig3.png)
