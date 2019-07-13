# Nereid - Predictive Autoscaling for Kubernetes
Nereid (pronounced  neer-ee-id) is a predictive cluster autoscaler for Kubernetes that's designed to run anywhere.
Nereid relies on machine learning to anticipate capacity requirements for your K8s cluster and provisions resources
accordingly. This helps to avoid "provisioning lag" when infrastructure demands increase rapidly, and also helps to terminate
instances faster when they are no longer required.

The longer Nereid is in service, the smarter it gets by continuously learning about your cluster's unique capacity
requirements.

Nereid is free open source software available under the Apache 2.0 License.

## Project Status
Nereid is in the early stages of development, and maintained by the Scott Crespo of Konture Technology Servies and
Jason Van Brackel of Rancher Labs.

Nereid is based on Konture's proprietary autoscaling service for AWS EC2, and leverages nearly 2 years of R&D. Konture is
making its software available for free to the Kubernetes community to usher in a new era of A.I.-driven, platform-agnostic
container management.

## Roadmap

| Phase | Objectives | Date |
| --- | --- | --- |
| 1 | Working POC on Kubernetes using Prometheus metrics. Support autoscaling based on CPU, RequestCount, Network Usage, and Memory Pressure | Q3 2019 |
| 2 | Develop pre-trained, "seed" ML models based on industry partner data | Q1 2020 |
| 3 | Beta | Q2 2020 |

## We Need Your Help!
We can't achieve our vision without help from the community!

### Companies
If you run Kubernetes in production, the Nereid Project is in need of anonymized data about your infrastructure utilization to
develop more advanced predictive machine learning models. You'll benefit by helping accelerate the project, as well as
received additional promotions and visibility via the project's GitHub repository and website.

### Individuals
Data scientists, software developers, and devops specialists are all encouraged to contribute to the project. We can't do this
without you!

## Maintainers

| Name | Contact |
| --- | --- |
| Scott Crespo | scott@konture.io |
| Jason van Brackel | jvb@rancher.io |


## Partners

[Konture Technology Services](https://konture.io)
