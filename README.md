# Technical Training - Tekton & ArgoCD
## What is it?
The *Technical Training - Tekton & ArgoCD* is a one-day learning experience for developers who want to understand and make use of Tekton and ArgoCD to setup a CI/CD pipeline and to automate their deployments on OpenShift in their daily work. They learn everything they need to understand the concepts, the architectural principles and components of Tekton & ArgoCD for successfully discussing and developing OpenShift at a customer site from a developer’s perspective.

### Key Takeaways
- Benefits of Tekton & ArgoCD on OpenShift
- How to effectively setup and demonstrate a Tekton pipeline
- How to effectively setup and demonstrate deployment automation with ArgoCD
- Using Kustomize to redeploy your Application

## Target Audience
- (Technical) Sales Engineers
- Delivery
- (Technical) Solution Architects
- Developers
- DevOps

## Prerequisites
- Basic knowledge of Red Hat 
- Basic understanding of Containers and Container Images
- Basic understanding of OpenShift and / or Kubernetes
- Java or any other programming language

## AGENDA
The next iteration of this Technical Training happens on September 26th 2024. Times in Central European Time.

If you want to participate, please go [here](https://connect.redhat.com/en/training/emea/technical-training-tekton-argocd) and register for free.


| Start     | End       | Topics                                                                                           |
| --------- | --------- | ------------------------------------------------------------------------------------------------ |
| 9:00      | 9:30      | Intro & Welcome                                                                                  |
| 9:30      | 11:00     | Application Packaging - Kustomize - Helm Charts - Kubernetes Operators                           |
| 11:00     | 12:30     | CI/CD - OpenShift Pipelines - Tekton - Tekton Security - Working with the examples #1            |
| **12:30** | **13:30** | **Lunch Break**                                                                                  |
| 13:30     | 15:30     | GitOps - Basics / Concepts - Using ArgoCD - Working with the examples - Building a complete demo |
| 15:30     | 16:00     | Open Questions / Answers                                                                         |


## Resources
The slides and presentations can be found in this repository under [material](material).


## Accompanying eBook
The accompanying free eBook of this workshop is [Getting GitOps](https://developers.redhat.com/e-books/getting-gitops-practical-platform-openshift-argo-cd-and-tekton), which has been published by [Red Hat Developers](https://developers.redhat.com/). 

## Demo Repositories & Requirements
All sources and demos are publicly available on GitHub. 
- [Basic Book Examples](https://github.com/wpernath/book-example.git)
- [Basic Book Example Config](https://github.com/wpernath/person-service-config.git)
- [GrumpyCat Example Game](https://github.com/wpernath/quarkus-grumpycat.git)
- [GrumpyCat Example Config](https://github.com/wpernath/grumpycat-config.git)


## Addional Resources
If you want to deepen your knowledge on several topics, have a look at the following blog series on **Automated Application Packaging and Distribution with OpenShift** which you could read here: 

(BTW, the blog series has been rewritten and published by [RedHat Developers](https://developers.redhat.com/e-books/getting-gitops-practical-platform-openshift-argo-cd-and-tekton)). 

- [Chapter zero](https://www.opensourcerers.org/2021/12/20/how-to-quickly-create-a-crud-service-with-quarkus/) talks about creating the CRUD service with Quarkus.

- [Chapter one](https://www.opensourcerers.org/2021/04/26/automated-application-packaging-and-distribution-with-openshift-part-12/) talks about container images and explains all the basic files and gives you a guide through OpenShift Templates and Kustomize as a base technology for application packaging
- [Chapter two](https://www.opensourcerers.org/2021/05/24/automated-application-packaging-and-distribution-with-openshift-part-23/) provides an overview of the various packaging formats, namely Helm Charts and Kubernetes Operators, and explains how they differ from each other and how to create them
- [Chapter three](https://www.opensourcerers.org/2021/07/26/automated-application-packaging-and-distribution-with-openshift-tekton-pipelines-part-34-2/) gives you a detailed view of Tekton / OpenShift Pipelines and helps you to quickly start your CI/CD process
- [And finally chapter four](https://www.opensourcerers.org/2021/09/06/automated-application-packaging-and-distribution-with-openshift-gitops-and-argocd-part-44) provides a detailed overview of GitOps and how to use it with OpenShift. 

