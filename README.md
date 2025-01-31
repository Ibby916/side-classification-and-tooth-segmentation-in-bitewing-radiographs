# Automating Side Classification and Tooth Segmentation with Numbering in Bitewing Radiographs Using Deep Learning


## This study is currently in the process of being published in a journal under Springer Nature.

In dental diagnosis, the analysis of bitewing radiographs is crucial for detecting, monitoring, and
treating dental issues. Two crucial steps in analyzing bitewings are distinguishing between the left
and right radiographs along with accurately identifying, numbering, and segmenting each tooth. Traditional methods of these steps in analyzing bitewings are time-consuming, labor-intensive, and prone
to variability in interpretation, leading to diagnostic errors and inconsistent treatment outcomes. To
address these issues, this study proposes a comprehensive framework for classifying radiographs (left
vs. right) and accurately numbering and segmenting teeth using CNN-based classifiers (CNN, VGG19,
ResNet50, and DenseNet-121) and instance segmentation models (Mask R-CNN, Cascade Mask R-
CNN, and SOLOv2) respectively. The CNN model emerged as the best-performing model, achieving
a flawless score of 1.00 across all evaluation metrics in side classification. For segmentation and num-
bering, SOLOv2 outperformed all other models. It showed improvements in mean Average Precision
(mAP) by 11.2%, from 0.762 to 0.874, and improvements in mean Average Recall (mAR) by 12.1%,
from 0.809 to 0.930, both calculated across IoU thresholds of 50 to 95, and compared to both the
models trained and those from previous studies. This framework improves the accuracy and efficiency
of dental diagnostics, offering a reliable alternative to traditional methods while setting the stage for
future innovations.

---

## Overall framework
![Fig. 1 Overall classification and segmentation framework](classification-and-segmentation-framework.svg)
**Fig. 1 Overall classification and segmentation framework**
