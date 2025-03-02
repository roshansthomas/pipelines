[![Coverage Status](https://coveralls.io/repos/github/kubeflow/pipelines/badge.svg?branch=master)](https://coveralls.io/github/kubeflow/pipelines?branch=master)
[![SDK Documentation Status](https://readthedocs.org/projects/kubeflow-pipelines/badge/?version=latest)](https://kubeflow-pipelines.readthedocs.io/en/stable/?badge=latest)
[![SDK Package version](https://img.shields.io/pypi/v/kfp?color=%2334D058&label=pypi%20package)](https://pypi.org/project/kfp)
[![SDK Supported Python versions](https://img.shields.io/pypi/pyversions/kfp.svg?color=%2334D058)](https://pypi.org/project/kfp)

## Overview of the Kubeflow pipelines service

[Kubeflow](https://www.kubeflow.org/) is a machine learning (ML) toolkit that is dedicated to making deployments of ML workflows on Kubernetes simple, portable, and scalable.

**Kubeflow pipelines** are reusable end-to-end ML workflows built using the Kubeflow Pipelines SDK.

The Kubeflow pipelines service has the following goals:

* End to end orchestration: enabling and simplifying the orchestration of end to end machine learning pipelines
* Easy experimentation: making it easy for you to try numerous ideas and techniques, and manage your various trials/experiments.
* Easy re-use: enabling you to re-use components and pipelines to quickly cobble together end to end solutions, without having to re-build each time.

## Installation

* Install Kubeflow Pipelines from choices described in [Installation Options for Kubeflow Pipelines](https://www.kubeflow.org/docs/pipelines/installation/overview/).

* :star: [Alpha] Starting from Kubeflow Pipelines 1.7, try out [Emissary Executor](https://www.kubeflow.org/docs/components/pipelines/installation/choose-executor/#emissary-executor). Emissary executor is Container runtime agnostic meaning you are able to run Kubeflow Pipelines on Kubernetes cluster with any [Container runtimes](https://kubernetes.io/docs/setup/production-environment/container-runtimes/). The default Docker executor depends on Docker container runtime, which will be deprecated on Kubernetes 1.20+.

## Documentation

Get started with your first pipeline and read further information in the [Kubeflow Pipelines overview](https://www.kubeflow.org/docs/components/pipelines/introduction/).

See the various ways you can [use the Kubeflow Pipelines SDK](https://www.kubeflow.org/docs/pipelines/sdk/sdk-overview/).

See the Kubeflow [Pipelines API doc](https://www.kubeflow.org/docs/pipelines/reference/api/kubeflow-pipeline-api-spec/) for API specification.

Consult the [Python SDK reference docs](https://kubeflow-pipelines.readthedocs.io/en/stable/) when writing pipelines using the Python SDK.

Refer to the [versioning policy](./docs/release/versioning-policy.md) and [feature stages](./docs/release/feature-stages.md) documentation for more information about how we manage versions and feature stages (such as Alpha, Beta, and Stable).

## Contributing to Kubeflow Pipelines

Before you start contributing to Kubeflow Pipelines, read the guidelines in [How to Contribute](./CONTRIBUTING.md). To learn how to build and deploy Kubeflow Pipelines from source code, read the [developer guide](./developer_guide.md).


## Kubeflow Pipelines Community Meeting

The meeting is happening every other Wed 10-11AM (PST)
[Calendar Invite](https://calendar.google.com/event?action=TEMPLATE&tmeid=NTdoNG5uMDBtcnJlYmdlOWt1c2lkY25jdmlfMjAxOTExMTNUMTgwMDAwWiBqZXNzaWV6aHVAZ29vZ2xlLmNvbQ&tmsrc=jessiezhu%40google.com&scp=ALL) or [Join Meeting Directly](https://meet.google.com/phd-ixfj-kcr/)

[Meeting notes](http://bit.ly/kfp-meeting-notes)

## Kubeflow Pipelines Slack Channel

[#kubeflow-pipelines](https://kubeflow.slack.com)

## Blog posts

* [Getting started with Kubeflow Pipelines](https://cloud.google.com/blog/products/ai-machine-learning/getting-started-kubeflow-pipelines) (By Amy Unruh)
* How to create and deploy a Kubeflow Machine Learning Pipeline (By Lak Lakshmanan)
  * [Part 1: How to create and deploy a Kubeflow Machine Learning Pipeline](https://towardsdatascience.com/how-to-create-and-deploy-a-kubeflow-machine-learning-pipeline-part-1-efea7a4b650f)
  * [Part 2: How to deploy Jupyter notebooks as components of a Kubeflow ML pipeline](https://towardsdatascience.com/how-to-deploy-jupyter-notebooks-as-components-of-a-kubeflow-ml-pipeline-part-2-b1df77f4e5b3)
  * [Part 3: How to carry out CI/CD in Machine Learning (“MLOps”) using Kubeflow ML pipelines](https://medium.com/google-cloud/how-to-carry-out-ci-cd-in-machine-learning-mlops-using-kubeflow-ml-pipelines-part-3-bdaf68082112)
* [Kubeflow Pipelines meets Tekton](https://developer.ibm.com/blogs/kubeflow-pipelines-with-tekton-and-watson/) (By Animesh Singh)
## Acknowledgments

Kubeflow pipelines uses [Argo Workflows](https://github.com/argoproj/argo-workflows) by default under the hood to orchestrate Kubernetes resources. The Argo community has been very supportive and we are very grateful. Additionally there is Tekton backend available as well. To access it, please refer to [Kubeflow Pipelines with Tekton repository](https://github.com/kubeflow/kfp-tekton).

## Survey
Please help us to provide your feedback [here](https://amazonmr.au1.qualtrics.com/jfe/form/SV_3fNc9oH4ql0guCq?Session=HAN7). Participants who complete the surveys from AWS Innovate Online Conference – AI/ML Edition will receive a gift code for USD25 in AWS credits. AWS credits will be sent via email by 31 March, 2022.