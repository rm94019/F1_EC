page_type	languages	products	description
sample
python
azure
azure-machine-learning-service
azure-devops
Code which demonstrates how to set up and operationalize an MLOps flow leveraging Azure Machine Learning and Azure DevOps.
MLOps with Azure ML
CI: Build Status

CD: Build Status

MLOps will help you to understand how to build a Continuous Integration and Continuous Delivery pipeline for an ML/AI project. We will be using the Azure DevOps Project for build and release/deployment pipelines along with Azure ML services for model retraining pipeline, model management and operationalization.

ML lifecycle

This template contains code and pipeline definitions for a machine learning project that demonstrates how to automate an end to end ML/AI workflow.

Architecture and Features
Architecture Reference: Machine learning operationalization (MLOps) for Python models using Azure Machine Learning

This reference architecture shows how to implement continuous integration (CI), continuous delivery (CD), and retraining pipeline for an AI application using Azure DevOps and Azure Machine Learning. The solution is built on the scikit-learn diabetes dataset but can be easily adapted for any AI scenario and other popular build systems such as Jenkins and Travis.

The build pipelines include DevOps tasks for data sanity tests, unit tests, model training on different compute targets, model version management, model evaluation/model selection, model deployment as realtime web service, staged deployment to QA/prod and integration testing.

Prerequisite
Active Azure subscription
At least contributor access to Azure subscription
Getting Started
To deploy this solution in your subscription, follow the manual instructions in the getting started doc. Then optionally follow the guide for integrating your own code with this repository template.

Repo Details
You can find the details of the code and scripts in the repository here

References
Azure Machine Learning (Azure ML) Service Workspace
Azure ML CLI
Azure ML Samples
Azure ML Python SDK Quickstart
Azure DevOps
Contributing
This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit https://cla.microsoft.com.

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the Microsoft Open Source Code of Conduct. For more information see the Code of Conduct FAQ or contact opencode@microsoft.com with any additional questions or comments.
