## CURVETE: Curriculum Learning and Progressive Self-supervised Training for Medical Image Classification

## Introduction

CURVETE is a novel deep learning model developed to enhance classification performance in medical image classification to handle two major challenges in medical imaging: limited labeled data and irregular class distribution. By leveraging a curriculum learning strategy with progressive sample decomposition, the model effectively extracts meaningful features and improves generalizability. CURVETE applies self-supervised learning on unlabeled data and integrates class decomposition to enhance classification performance, even in scenarios with imbalanced datasets.

### Datasets Used
CURVETE has been evaluated on three distinct medical image datasets:
1. **Brain Tumor Dataset**. [here](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
2. **Digital Knee X-ray Dataset**.
3. **Mini-DDSM Dataset**.

### Requirements
To run this project, you'll need the following dependencies:
- **Python**: 3.8
- **TensorFlow**: Version 2.13
- Other required libraries: 
  - `NumPy`
  - `Matplotlib`
  - `scikit-learn`
  - `OpenCV`
 

https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection
###Citation
If you use this code or method in your research, please cite the following paper:
