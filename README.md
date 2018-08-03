# Docker Enterprise Edition Exercises

No matter where you are in your Docker journey, these exercises are meant to help demystify some Docker concepts and guide users along specific learning path depending on their use case and expertise level.

These workshops are only available to people in a pre-arranged workshop. That may happen through a [Docker Meetup](https://events.docker.com/chapters/), a conference workshop that is being led by someone who has made these arrangements, or special arrangements between Docker and your company. The workshop leader will provide you with the URL to a workshop environment that includes [Docker Enterprise Edition](https://www.docker.com/enterprise-edition). The environment will be based on [Play with Docker](https://labs.play-with-docker.com/).


## [Docker 101 - Linux](https://training.play-with-docker.com/dev-stage1/)
An introduction to Docker on Linux that takes you through the basics of the platform, building your first containers, and deploying them in an orchestration system. People taking these labs will come out understanding the basics of Docker and orchestration.

## [Kubernetes on Docker for Mac and Docker for Windows](/kubernetes-desktop.md) 
This lab will cover the basics of using Kubernetes on Docker for Mac and Docker for Windows. People taking this lab will gain an understanding of basic concepts of Kubernetes and how to create your cluster on your desktop.

## [Modernizing Traditional Java Apps](/mta-java.md)
This lab will take a traditional, Java EE monolithic application and show you how to containerize it, and then break out a few pieces to have a more modern, modular deployment of the application built on Docker EE. People taking this lab will understand the basics of application modernization and Docker EE.

## [Service Discovery and Load Balancing for a microservices application on Docker EE and Kubernetes](http://success.docker.com/article/ucp-service-discovery)
This reference architecture covers the solutions that Docker EE 2.0 provides in the topic areas of service discovery and load balancing for both swarm mode as well as Kubernetes workloads. In swarm mode, Docker uses DNS for service discovery as services are created, and different routing meshes are built into Docker to ensure your applications remain highly available. The release of UCP 3.0 introduces a versatile and an enhanced version of application layer (Layer 7) routing mesh called the Interlock Proxy that routes HTTP traffic based on DNS hostname. After reading this document, you will have a good understanding of how Interlock Proxy works and how it integrates with the other service discovery and load balancing features native to Docker.

Additionally, UCP 3.0 introduces enterprise support for using Kubernetes as the orchestrator of your application workloads. This document will also provide a good understanding of how to use Kubernetes resource objects within Docker EE to deploy, run, and manage application workloads.
