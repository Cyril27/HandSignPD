# HandSignPD

Recent advances in artificial intelligence and deep learning have enabled the development of increasingly data-driven tools for detecting neuropathologies like Parkinson’s Disease. However, the need for early-stage, non-invasive diagnostic methods has driven the use of handwriting tasks as a promising alternative to clinical data like MRI scans. This study leverages the power of multimodal models to define optimal predictors of Parkinson’s Disease by considering model architecture, data augmentation and hyperparameters tuning. Our approach achieved excellent classification performance, reaching an accuracy of over 99% through the use of intermediate fusion and contrast data augmentation. Furthermore, the capabilities of transfer learning and integration of additional modalities highlights the potential for reliable diagnosis when a holistic understanding of such multi-causal pathologies is performed. 

# Repository structure
The repository contains all the Python code needed to build, train and validate the pipeline defined above. A brief description of each python file is given below.

## IPYNB notebooks
**multimodal-main** : Main investigation of the different multimodal architectures, the data augmentation and the robustness of each model\
**transfer-learning** : Study the Transfer learning capabilities of the best performing models on a second dataset\
**metadata-modality** : Modification of the best performing architecture to introduce a metadata modality

