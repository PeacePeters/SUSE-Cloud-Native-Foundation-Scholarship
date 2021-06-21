# Introduction to Cloud Native Fundamentals

## Lesson Outline
- Introduction to Cloud Native
+ CNCF and Cloud Native tooling
* Stakeholders
- Tools, Environment & Dependencies

### Introduction to Cloud Native

Cloud-native refers to the set of practices that empowers an organization to build and manage applications at scale.  It is an approach to building and running applications that exploits the advantages of the cloud computing delivery model.
Cloud native technologies empower organizations to 
* Build and run scalabe applications
+ Using modern, dynamic environments such as on-prem, public or hybrid cloud

> The key to cloud native deployment is `speed` and `agility`, or how quickly an organization can respond to change and increase its feature velocity.

Containers, microservices, declarative APIs, etc. are closely associated with cloud-native terminology. What then are containers?

Containers are:
- Small units of an application
* Deployed fast and resiliently
- Well fitted with microservice-based architecture

> Microservices are used to manage and configure a collection of small, independent services that can be easily packaged and executed within a container.

### CNCF and Cloud-Native Tooling

With the use of containers came the need for tools that can manage containers at scale. Examples are of such tools are Docker Swaem, Apache Mesos & Kubernetes. However, Kubernetes took the lead in defining how containerized workloads should be deployed, managed, and configured.

> Kubernete is a container orchestrator that automates the configuration, management, and scalability of an application.

Facts about Kubernetes and CNCF

Screenshot 2021-06-21 at 16.18.54

Overall, Kubernetes is a container orchestrator that is capable to solutionize the integration of the following functionalities:

**Funtionalities** | **Usage**
--- | --- 
Runtime | For application execution environment
Networking | For application connectivity
Storage | For application resources
Service Mesh | For granular control of the traffic within a cluster
Logs and metrics | To construct the observability stack
Tracing | For building the full request journey