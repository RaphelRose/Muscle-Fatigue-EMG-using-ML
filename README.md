# Muscle-Fatigue-EMG-using-ML
## Abstract
Muscle fatigue is a commonly observed phenomenon in muscles when exposed to repeated or prolonged contractions, causing reduced muscle performance and increased susceptibility to injuries. Early detection of muscle fatigue is critical in most sports where it improves performance and prevents injury and healthcare, where it facilitates the monitoring and rehabilitation of patients. Electromyography (EMG) is a non-invasive tool for evaluating muscle activity by recording electrical signals generated during muscle contractions. This will provide valuable insights for identifying muscle fatigue. This project introduces a machine learning-based approach, specifically implementing Support vector machine (SVM), for the EMG signals classification of the muscle fatigue. Our scope is to develop a proper and robust model that enables the EMG signals to accurately classify the states as both fatigued and non-fatigued. The methodology includes: preprocessing of the EMG dataset, extraction of key features, and applying a machine learning model for accomplishing the classification. 

## Dataset Description
This work involved the use of two independent data sets to analyse muscle fatigue with electromyography signals. One is a data set with baseline EMG signals obtained from resting conditions, thereby creating a reference for the baseline muscle activity in the absence of fatigue. The second set of data includes the signals obtained during individuals carrying a load with elbow flexed at a particular angle. These datasets would form a well-rounded foundation on which muscle performance and fatigue are being compared across conditions. The EMG signal baseline and walking would then be differentiated into muscle fatigue versus non-fatigue states with the aid of a SVM classifier.

## Methodology
## 1. Dataset Collection  
- **Baseline EMG Signals:** Collected from resting conditions.  
- **Fatigue EMG Signals:** Collected while lifting a load with elbow flexed.  

## 2. Preprocessing  
- Raw EMG signals are filtered and standardized.  
- The first dataset requires preprocessing, while the second is already clean.

## 3. Feature Extraction
- To classify muscle fatigue, the following features are extracted from the EMG signals:  
- **Mean Absolute Value (MAV):** Measures the overall amplitude of the signal.  
- **Root Mean Square (RMS):** Indicates the signal power and energy.
  
## 4. Classification Model  
- Support Vector Machine (SVM) is used for classification.  
- MATLAB scripts preprocess the signals and train the model.

## Result
The Support Vector Machine (SVM) model was evaluated using 5-fold cross-validation on the dataset for detecting Fatigue and Non-Fatigue states from sEMG signals. The model demonstrated exceptional performance, achieving perfect results across all evaluation metrics, including:
- Accuracy: 100%
- Precision: 1.0
- Recall: 1.0
- F1-Score: 1.0
- Specificity: 1.0

## Limitation
This study's dataset was small, and that possibly contributed to the perfect performance. The generalizability of the model to larger, more diverse datasets from possibly different fitness levels and medical conditions was not tested.

## Reference
- Sapsanis, C., Tzes, A., & Georgoulas, G. (2013). sEMG for Basic Hand movements [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5TK53.
- A. Ebied, A. M. Awadallah, M. A. Abbass and Y. El-Sharkawy, 
"Upper Limb Muscle Fatigue Analysis Using Multi-channel Surface EMG," 
2020 2nd Novel Intelligent and Leading Emerging Sciences Conference (NILES), 2020,
pp. 423-427, doi: 10.1109/NILES50944.2020.9257909.



