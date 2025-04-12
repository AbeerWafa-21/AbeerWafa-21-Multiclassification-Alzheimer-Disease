# AbeerWafa-21-Multiclassification-Alzheimer-Disease
Alzheimer’s Disease (AD) is a progressive neurodegenerative disorder characterized by a gradual decline in cognitive function, memory, and behavioral capabilities. It is the most common form of dementia, affecting millions of individuals worldwide, and currently has no known cure. Early and accurate diagnosis of Alzheimer’s, particularly in its prodromal and mild stages, is critical for effective disease management and therapeutic intervention. Magnetic Resonance Imaging (MRI) has emerged as a valuable non-invasive tool for capturing structural brain changes associated with the progression of AD. However, manual analysis of MRI data remains time-consuming and prone to inter-observer variability, underscoring the need for automated, objective, and reliable diagnostic frameworks.

In this study, we propose a deep learning-based approach for the automated multiclass classification of Alzheimer’s disease stages, focusing on the four clinically relevant categories: Non-Demented, Very Mild Demented, Mild Demented, and Moderate Demented. We evaluate the efficacy of several deep learning and hybrid models, including:

- Convolutional Neural Networks (CNN)

- CNN integrated with Support Vector Machines (CNN-SVM)

- VGG16 coupled with SVM (VGG16-SVM)

 A hybrid Convolutional Neural Network with Long Short-Term Memory units (CNN-LSTM)

Among these, the CNN-LSTM model demonstrated the most promising results, achieving consistently high classification performance across multiple validation scenarios. This architecture combines the powerful spatial feature extraction capabilities of CNNs with the sequential modeling strength of LSTMs, enabling the network to learn complex temporal dependencies within the MRI data. The performance of the CNN-LSTM model was confirmed across diverse case evaluations, reinforcing its robustness and reliability in practical diagnostic settings.

The findings of this work highlight the critical role of sequential deep learning frameworks in advancing the field of medical image analysis. By integrating spatial and temporal modeling, the CNN-LSTM architecture offers a potent tool for supporting the early and accurate classification of Alzheimer’s Disease, with potential translational value in clinical decision-making and longitudinal monitoring.

