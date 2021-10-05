# Interpretable-machine-Learning-Using-LIME
## Need for Interpretable and Explainable Machine Learning
This repository demonstrates use of Locally Interpretable Model Agnostic Explanations (LIME) to explain predictions of black-box models.
Machine Learning is used for many real-life prediction problems in healthcare, banking, finance and human resources. Some examples of these prediction problems are using transaction data to predict credit card fraud, using appli ation data to decide whether an applicant should be given a loan and using medical imagging data to diagnose a patient with a medical condition. While adopting any such system whose decisions directly impact humans, trust is a crucial factor in determining whether the decisions given by the machine learning models are used as a basisi to take any action. If the predictions given by models are explainable and can be interpreted by humans, it increases the trusttworthiness of the system.

## Black Box nature of Machine Learning models
With the increased prevelance of cheap computingpower, complex machine learning models like neural networks have become prevalant in practice. But their superioir predictive performance comes at a cost: they are black-boxes and there is no way to infer how they arrived at the prediction. This creates the need for frameworks and techniques that can give the decision maker an insight into learning process of the model. It can also help identfy issues like data leakage and model bias. It can be used to answer social questions like: Are loan being denied to certain applicants because they are black? Is a patient being denied treatment because they are female?

## Local Interpretable Model Agnostic Explanation (LIME)
LIME Framwework aims to obtain explanation for individual predictions by fitting surrogate models in the section of feature space which is proximal to the chosen data instance, instead of trying to explain a black box model entirely. It is model agnostic as the local surrogate models could be built to explain the predictions given by any black box method- neural network, random forest of XGboost. The local surrogate models are trained on new data instances created by adding disturbances to the data instance for which explanations are needed.

The process to obtain LIME is as follows:





**References**
1. https://christophm.github.io/interpretable-ml-book/
2.https://c3.ai/glossary/data-science/lime-local-interpretable-model-agnostic-explanations/
3. https://www.youtube.com/watch?v=hUnRCxnydCc
