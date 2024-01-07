# MLOps on AWS Cloud

**MLOps** (or Machine learning operations) is one of practices, where it starts to gain traction and have been implemented across multiple organisations. It aims to streamline and enhance the end-to-end process of developing, deploying, and maintaining machine learning models. Moreover, it can be expand to cover data sourcing, data labelling, and data versioning.

However, in its core, **collaboration and communication** are the key components. It involves cross-functional teams who are not limited to data scientists, data engineers, ML engineers, and operation teams working in collaboration to integrate ML into existing systems (or new system).

**Automation** is also the crucial role in MLOps by standardize and streamline the processes to reduce manual errors, ensure reproducibility, and reduce the time to deployment.

<img src="/img/mlops-maturity.png">

## What is in this repository?
This repository will gather the sample solutions of how to implement MLOps on AWS Cloud utilising **Amazon SageMaker Pipelines** at its core.

**Solution**:
- [Implement AutoML step to SageMaker Pipelines](/automl-step): This MLOps covers data processing, AutoML, evaluate the best model candidate, and register the best model to SageMaker model register with the condition that the best model needs to have F1 score greater than or equal to 0.8. You can view this as <b><u>initial stage</u></b> of your MLOps journey.
