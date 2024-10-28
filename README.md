# EcoSort: Automated Image Segmentation for Sorting Recyclable Materials

**Project by HKN, IEEE BVCOE**

EcoSort is an automated waste sorting system designed to address the growing challenge of effective recycling. Leveraging machine learning algorithms, this system identifies and categorizes recyclable materials from mixed waste streams with high accuracy, offering a scalable solution that reduces manual sorting efforts.

[![Video Demonstration](https://img.icons8.com/color/48/000000/youtube-play.png)](https://drive.google.com/file/d/1mSvhtZdX1pCfOrS7TrCCcS3K6CNKHRDO/view?usp=sharing)  
*Click the icon above to watch the project demonstration on Google Drive.*

---

## Table of Contents

- [Abstract](#abstract)
- [Project Objectives](#project-objectives)
- [Models and Techniques](#models-and-techniques)
- [Results](#results)
- [Conclusion](#conclusion)
- [Requirements](#requirements)

---

## Abstract

The EcoSort project aims to develop an efficient waste management solution that uses machine learning models to automate the classification of recyclable materials. This four-week project involved the development of a computer vision system capable of distinguishing materials like plastic, metal, and glass with high accuracy.

EcoSort addresses the critical challenges associated with manual sorting, providing a scalable solution that enhances recycling efficiency while minimizing operational costs and human effort.

---

## Project Objectives

1. **Implement and evaluate multiple deep learning architectures** for recyclable material classification.
2. **Compare the performance of different models** to identify the most accurate and efficient approach.
3. **Develop a solution** suitable for real-world deployment scenarios with potential for scalability.

---

## Models and Techniques

### Models Used

- **VGG Models** (VGG16 & VGG19)
- **ResNet50**
- **InceptionV3**
- **MobileNetV3**
- **CNN**
- **EfficientNet**

### Evaluation Metrics

- Classification Accuracy
- Precision and Recall
- F1-score
- Confusion Matrix
- Computational Requirements
- Performance Curves

---

## Results

The following table shows the accuracy achieved by each model:

| Model             | Accuracy (%) |
|-------------------|--------------|
| ResNet50 (with Transfer Learning) | 92.51% |
| VGG19 (with Transfer Learning)    | 90.73% |
| InceptionV3                        | 88.98% |
| VGG16 (Basic)                      | 87.15% |
| MobileNetV3                        | 86.26% |
| ResNet50 (Basic with Softmax)      | 80.94% |
| CNN                                | 67.62% |
| EfficientNet                       | 29.79% |

**Model Performance Highlights**:
- **Best Performance**: ResNet50 (with Transfer Learning) at 92.51%
- **Runner-Up**: VGG19 (with Transfer Learning) at 90.73%
- These models are both suitable for real-world production deployment.

---

## Conclusion

Based on the results, **ResNet50 with transfer learning** is the most effective model for classifying recyclable materials, achieving an accuracy of 92.51%. The high accuracy achieved by ResNet50 and VGG19 suggests they are suitable for deployment in environments where accuracy is critical.

**Practical Implications**:
- High-accuracy models are viable for large-scale recycling facilities where efficient sorting is essential.
- Lighter models like VGG16 may serve better in resource-constrained environments while maintaining reasonable accuracy.

---

## Requirements

To run this project, install the dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
