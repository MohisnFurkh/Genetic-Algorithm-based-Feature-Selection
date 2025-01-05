# Deep Learning and Genetic Algorithm-based Ensemble Model for Breast Ultrasound Classification

This repository contains the official implementation of "Deep learning and genetic algorithm-based ensemble model for feature selection and classification of breast ultrasound images" https://www.sciencedirect.com/science/article/abs/pii/S0262885624001227.

## Abstract
Feature extraction and selection are important techniques in the classification of medical images. Extraction of key features and selection of relevant features are the preliminary processes that are essential for identifying the shape of an object or diagnosis of a tumor in images. In this study, we conduct a thorough comparison of deep neural networks' performance. The comparison of the networks infers MobileNet as optimal for feature extraction from medical images, where it has minimal parameters and high validation accuracy. For feature selection, we employ the Genetic Algorithm (GA) because of its proficiency in handling high-dimensional and complex feature space. GA's iterative process aligns well with the unique characteristics of breast ultrasound (BUS) images, which enhances its efficacy in selecting salient features of BUS images. An ensemble model, capitalizing on the collective decision-making capabilities of multiple classifiers based on a weighted voting scheme for classification, is proposed. Empirical evaluations are conducted using two publicly available BUS image datasets, BUSI and UDIAT. The proposed model demonstrates a notable improvement of approximately 4% and 9% in accuracy for the BUSI and UDIAT, respectively. The improved diagnostic accuracy in breast abnormality identification allows for early abnormality diagnosis. This improves treatment outcomes for breast cancer patients and highlights the practical value of the proposed method for improving BUS image categorization.

## Requirements
- Python 3.7+
- TensorFlow


## Installation
```bash
pip install -r requirements.txt
