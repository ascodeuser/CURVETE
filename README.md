## CURVETE: Curriculum Learning and Progressive Self-supervised Training for Medical Image Classification

## Introduction

CURVETE is a self-supervised learning model that leverages an anti-curriculum learning strategy to enhance the training of unlabelled samples through sample decomposition. This approach aims to enhance the effectiveness of self-supervised learning by extracting meaningful features across a broad range of solutions, thereby improving feature transferability to a new dataset with limited samples. In the downstream task, CURVETE also applies class decomposition, guided by anti-curriculum learning, to handle irregular class distributions more effectively.


### Results
CURVETE has been evaluated on three medical image datasets: brain tumour, digital knee x-ray, and Mini-DDSM, using two different pre-trained networks. It achieved accuracies of 96.60% on the brain tumour dataset, 75.60% on the digital knee x-ray dataset, and 93.35% on the Mini-DDSM dataset using the baseline ResNet-50. Furthermore, the classification performance with the baseline DenseNet-121 achieved accuracies of 95.77%, 80.36%, and 93.22% on the brain tumour, digital knee x-ray, and Mini-DDSM datasets, respectively, outperforming other training strategies.

### Datasets Used
CURVETE has been evaluated on three distinct medical image datasets:
1. **Brain Tumor Dataset**. [here](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
2. **Digital Knee X-ray Dataset**. [here](https://data.mendeley.com/datasets/t9ndx37v5h/1)
3. **Mini-DDSM Dataset**. [here]( https://www.kaggle.com/datasets/cheddad/miniddsm2)

### Requirements
To run this project, you'll need the following dependencies:
- **Python**: 3.8
- **TensorFlow**: Version 2.13
- Other required libraries: 
  - `NumPy`
  - `Matplotlib`
  - `scikit-learn`
  - `OpenCV`

### Figure 1: Framework
<p align="center">
<img src="https://github.com/ascodeuser/CURVETE/raw/main/images/method.png" alt="Model Figure" width="500" style="display: block; text-align: left;"/>
  
</p>



### Citation
If you use this code or method in your research, please cite the following paper:

**CURVETE: Curriculum Learning and Progressive Self-supervised Training for Medical Image Classification, ICONIP 2025.**

*Asmaa Abbas, Mohamed Medhat Gaber, and Mohammed M. Abdelsamea*
