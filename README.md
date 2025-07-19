# Efficient-Focal-Loss-Function-for-Insurance-Fraud-Prediction

Abstract
 In the realm of insurance fraud prediction, handling class imbalance remains a critical challenge. This paper presents a novel multistage focal loss function designed to enhance the performance of machine learning models in such imbalanced settings by helping to escape local minima and converge to a good solution. Building upon the foundation of the standard focal loss, our proposed approach introduces a dynamic, multi-stage convex and nonconvex mechanism that progressively adjusts the focus on hard-to-classify samples across training epochs. This strategic refinement facilitates more stable learning and improved discrimination between fraudulent and legitimate cases. Through extensive experimentation on a real-world insurance dataset, our method achieved better performance than the traditional focal loss, as measured by Accuracy, precision, F1-score, recall and Area Under the Curve (ROC AUC) metrics on the auto insurance dataset. These results demonstrate the efficacy of the multistage focal loss in boosting model robustness and predictive accuracy in highly skewed classification tasks, offering significant implications for fraud detection systems in the insurance industry. An explainable model is included to interpret the results. 


**Dataset***:https://zenodo.org/records/13381118

For results in the excel file

convex== convex

multistage=multistage

nonconvex=nonconvex(gamma=2)

Hybrid=nonconvex(gamma=4)
