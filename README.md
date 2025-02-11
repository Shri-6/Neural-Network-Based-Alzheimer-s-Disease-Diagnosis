# Neural Network-Based Alzheimer's Disease Diagnosis: A Deep Learning Approach  

## Overview  
This project presents a novel hybrid Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) model for Alzheimer's disease (AD) diagnosis. By leveraging structural MRI scans and functional fMRI data, the model enhances precision and robustness in detecting AD. The proposed approach outperforms traditional standalone CNN and LSTM models, achieving high accuracy, sensitivity, and specificity.  

## Features  
- **Hybrid CNN-LSTM Model**: Extracts spatial features using CNNs and temporal patterns using LSTMs.  
- **High Accuracy**: The CNN-LSTM model achieves a validation accuracy of **92.13%**.  
- **Interpretability**: Saliency maps and attention mechanisms provide insights into AD biomarkers.  
- **Comparative Analysis**: Evaluates performance against traditional ML models and deep learning architectures.  
- **Dataset Augmentation**: Enhances model generalization by applying transformations like rotation, scaling, and noise addition.  

## Dataset  
The dataset comprises structural and functional neuroimaging data, categorized into:  
- **Non-Demented**  
- **Stage 1 Alzheimer's Disease**  
- **Stage 2 Alzheimer's Disease**  

## Model Architecture  
The CNN-LSTM model integrates:  
- **CNN Layers** for spatial feature extraction  
- **LSTM Layers** for capturing temporal dependencies  
- **Attention Mechanism** for enhanced interpretability  
- **Softmax Classifier** for multi-class classification  

## Performance Metrics  
| Metric         | Value |  
|---------------|-------|  
| Validation Accuracy | 92.13% |  
| Weighted F1 Score   | 0.9211 |  
| Training Accuracy   | 98.71% |  

## Publication  
This research has been published in the **2024 IEEE Students Conference on Engineering and Systems (SCES)**.  
You can read the full paper here:  
[Neural Network-Based Alzheimer's Disease Diagnosis: A Deep Learning Approach](https://ieeexplore.ieee.org/document/10652297)  

## Authors  
- **Shri Varshan Periyaswamy** (Vellore Institute of Technology, Chennai)  
- **Dr. Suganya R** (Vellore Institute of Technology, Chennai)  

## License  
This project is licensed under the **MIT License**.  

