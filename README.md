# Pulmo-TS2ONN

**Pulmo-TS2ONN: A Novel Triple Scale Self Operational Neural Network for Pulmonary Disorder Detection Using Respiratory Sounds**

**Authors: Arka Roy, Udit Satija**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/rsarka34/Pulmo-TS2ONN/blob/main/model/Pulmo-TS2ONN.ipynb)
[![Paper Link](https://img.shields.io/badge/Paper%20Link-IEEE%20Xplore-red)](https://ieeexplore.ieee.org/abstract/document/10473755)  

# Abstarct
<p align="justify">
Pulmonary disorders (PDs) are one of the substantial hazards to human life, which can be diagnosed by a variety of clinical modalities, including peak flowmeter and spirometry measurements, chest auscultation-based respiratory sound (RS) measurements, etc. Analyzing the acoustic RS measurements is one of the inexpensive yet essential diagnostic methods for identifying PDs as these RSs are correlated with structural flaws of the lungs that occur due to PDs. Additionally, the development of the digital stethoscope facilitates the continuous measurement of acoustic RSs of any individual, which can be exploited to identify a variety of PDs. In this article, we have proposed a triple time-frequency feature set driven triple-scale self-operational neural network (TS2ONN) architecture, namely Pulmo-TS2ONN, to classify a wide spectrum of PDs using the RSs. The proposed pulmo-TS2ONN comprises three major stages: preprocessing, triplet time-frequency feature set (TTFFS) extraction, and finally classification of seven class PDs by using TS2ONN architecture which utilizes the improved nonlinear neural backbone of self-operational neural network (SONN) in place of the linear neural architecture used in conventional deep learning (DL) networks. Upon experimental evaluation, the proposed framework outperforms the existing noteworthy research works by achieving the highest performance rates of 98.88%, 98.27%, and 99.84% for accuracy, sensitivity, and specificity, respectively. Lastly, the proposed framework is implemented on a quad-core ARM-A7-based Raspberry Pi-4 microcontroller, allowing the possibility of translating the research into real clinical situations for RS-based PD screening.  </p>

![pp](https://github.com/user-attachments/assets/161237f9-3f1d-47cd-9a5f-61c053772191)


# Dataset
- ICBHI Dataset: [![Paper Link](https://img.shields.io/badge/ICBHI%20Data-BHI%20Challenge-green)](https://bhichallenge.med.auth.gr/ICBHI_2017_Challenge)
- KAUH Dataset: [![Paper Link](https://img.shields.io/badge/KAUH%20Data-Mendeley%20Data-red)](https://data.mendeley.com/datasets/jwyy9np4gv/3)
- RespiratoryDatabase@TR: [![Paper Link](https://img.shields.io/badge/RD%20@TR-Mendeley%20Data-red)](https://data.mendeley.com/datasets/p9z4h98s6j/1)
![image](https://github.com/user-attachments/assets/6e4816eb-2860-4c31-bacf-c5e240e968b8)

# Performance
![image](https://github.com/user-attachments/assets/a8ce5581-48b1-4f5c-859e-5b89bca8213f)


# Cite as
A. Roy, U. Satija and S. Karmakar, "Pulmo-TS2ONN: A Novel Triple Scale Self Operational Neural Network for Pulmonary Disorder Detection Using Respiratory Sounds," in IEEE Transactions on Instrumentation and Measurement, vol. 73, pp. 1-12, 2024, Art no. 6502812, doi: 10.1109/TIM.2024.3378206.

```bibtex
@ARTICLE{10473755,
  author={Roy, Arka and Satija, Udit and Karmakar, Saurabh},
  journal={IEEE Transactions on Instrumentation and Measurement}, 
  title={Pulmo-TS2ONN: A Novel Triple Scale Self Operational Neural Network for Pulmonary Disorder Detection Using Respiratory Sounds}, 
  year={2024},
  volume={73},
  number={},
  pages={1-12},
  keywords={Databases;Lung;Chronic obstructive pulmonary disease;Asthma;Pneumonia;Neural networks;Diseases;Auscultation measurements;classification;pulmonary disorders (PDs);respiratory sounds (RSs);self-operational neural network (SONN)},
  doi={10.1109/TIM.2024.3378206}}
