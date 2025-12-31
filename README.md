# Towards Better-Calibrated ML Models for Reliable Network Intrusion Detection via Calibration-Aware SHAP-based Feature Selection

Authors: Hussein Fawaz, Fatima Ezzeddine, Silvia Giordano, Omran Ayoub

University of Applied Sciences and Arts of Southern Switzerland, Switzerland, Universita della Svizzera italiana, Switzerland `

This work has been published at the 2025 21th International Conference on Wireless and Mobile Computing, Networking and Communications (WiMob), Marrakesh, Morocco, 2025 in the GenXNet Workshop.

Link to paper: https://ieeexplore.ieee.org/document/11257482

For any collaboration or questions please contact the first author: hussein.fawaz@usi.ch

In case you use any piece of code or part of the pipeline, please cite this paper:

H. Fawaz, F. Ezzeddine, S. Giordano and O. Ayoub, "Towards Better-Calibrated ML Models for Reliable Network Intrusion Detection via Calibration-Aware SHAP-Based Feature Selection," 2025 21th International Conference on Wireless and Mobile Computing, Networking and Communications (WiMob), Marrakesh, Morocco, 2025, pp. 1-6, doi: 10.1109/WiMob66857.2025.11257482. 


Abstract:
Model calibration and feature selection are two critical aspects in developing reliable and accurate machine learning models. Calibration ensures that the model's confidence scores accurately reflect the true likelihood of correctness, which is essential in security-critical applications, like Network Intrusion Detection Systems (NIDS). Feature selection (FS), meanwhile, enhances model efficiency, interpretability, and generalization by identifying the most relevant inputs. However, it may also degrade model's calibration if not explicitly considered. Recently, Explainable Artificial Intelligence (XAI) methods, particularly Shapley Additive Explanations (SHAP), have proven effective in guiding the FS process. Yet, existing SHAP-based FS techniques typically focus on improving accuracy, often giving little attention to the impact of FS on model calibration, an aspect that is critical for reliable decision-making in high-stakes applications such as NIDS. In this work, we propose a novel approach that incorporates a calibration-aware loss function for XGBoost with SHAP-based Recursive Feature Elimination for FS to jointly improve both predictive accuracy and model calibration. Experiments on two benchmark NIDS datasets show that our approach can reduce Brier score and Expected Calibration Error by up to 3.5% and 84.8%, respectively, over uncalibrated baselines, and by up to 2.6% and 58.3% over standard calibration methods, while enhancing or maintaining predictive accuracy and number of features.

keywords: {Wireless communication;Accuracy;Explainable AI;Computational modeling;Network intrusion detection;Predictive models;Benchmark testing;Feature extraction;Calibration;Reliability;Intrusion Detection Systems;Model Calibration;Feature Selection;Explainable AI}
