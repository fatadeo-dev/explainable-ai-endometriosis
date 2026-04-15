# explainable-ai-endometriosis
Explainable AI for Endometriosis Diagnosis

A deep learning and explainable AI framework for non-invasive diagnosis of endometriosis, designed to improve clinical decision-making through transparency and multimodal learning.

Problem Statement
Endometriosis is a complex and often underdiagnosed condition due to the limitations of invasive diagnostic procedures and delayed symptom recognition.
This project addresses the challenge by developing an AI-driven, interpretable diagnostic system that supports early detection and improves trust in machine learning predictions.

Approach
This work combines deep learning, explainable AI, and multimodal data fusion:
Deep Neural Networks for classification
SHAP for feature-level interpretability
Grad-CAM for visual explanation of model predictions
Multimodal fusion of:
Medical imaging data
Simulated structured clinical features

Methodology
Image-based model training using medical datasets
Extraction of meaningful features from imaging data
Simulation of structured clinical dataset based on domain-informed patterns
Fusion of image + structured data at decision level
Application of XAI techniques (SHAP, Grad-CAM)
Evaluation using accuracy, interpretability, and clinical relevance

Key Contributions
Developed an interpretable deep learning model for medical diagnosis
Improved model transparency and trust using SHAP and Grad-CAM
Introduced a multimodal fusion strategy for enhanced performance
Designed a system suitable for real-world clinical deployment

Data
Medical imaging dataset (restricted due to privacy)
Simulated structured dataset derived from imaging insights

Note: Due to confidentiality, raw datasets are not publicly available. Synthetic/sample data may be added for demonstration purposes.

Publications
Explainable AI for Endometriosis Diagnosis (2025)
Enhancing Non-Invasive Diagnosis using Grad-CAM (2025)
Multimodal Fusion for Clinical Decision Support (2026)

Tech Stack 
Python
TensorFlow / PyTorch
Scikit-learn
SHAP
OpenCV
NumPy / Pandas

Impact
This project contributes to the growing field of AI in healthcare, focusing on building systems that are not only accurate but also interpretable, trustworthy, and deployable in real-world environments.

Author

Oluwayemisi Boye Fatade, PhD
Applied AI Researcher | Explainable AI | Healthcare AI
