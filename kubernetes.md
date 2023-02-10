What is Kubernetes?

Kubernetes is an open-source container orchestration system for automating the deployment, scaling, and management of containerised applications.

The system is built on a modular architecture, consisting of several core components such as etcd (a distributed key-value store that stores configuration data), 
API Server (main control plane that exposes Kubernetes API), Controller Manager (daemon responsible for managing state of Kubernetes objects), Scheduler (daemon 
responsible for scheduling pods), kubelet (daemon running on worker nodes that communicates with API server), and kubeproxy (network proxy running on worker nodes 
that maintains network connectivity between pods). It uses a declarative model for managing containers, where the user describes the desired state of the system and
the system makes sure that the actual state matches the desired state. Kubernetes provides features such as automatic scaling, self-healing, service discovery and
load balancing, 
automated rollouts and rollbacks, and automatic binpacking, making it a powerful and flexible platform for container orchestration that can be used to deploy and
manage cloud-native applications in a consistent and repeatable manner.

Applications:
-Deploying, scaling, and managing containerised applications
-Automatic failover and self-healing
-Service discovery and load balancing
-Automated rollouts and rollbacks
-Automatic binpacking

Advantages:
-Kubernetes is a portable and extensible platform, which means that it can run on various infrastructure (on-premises, public cloud, private cloud, and hybrid cloud).
-it provides automatic scaling and self-healing capabilities, making it easier to manage and maintain.
Kubernetes can be used to deploy and manage both stateless and stateful applications.
-it provides a centralised management and control plane for deploying, scaling and managing containerised applications.

In conclusion, Docker is an open-source platform that allows developers to easily create, deploy, and run applications in containers. Containers are lightweight, 
portable, and self-sufficient, and they can run on any infrastructure, including virtual machines and bare-metal servers.Kubernetes, on the other hand, is 
an open-source container orchestration system that automates the deployment, scaling, and management of containerised applications. Together, Docker and Kubernetes 
provide a powerful platform for building and deploying modern, cloud-native applications. The combination of Docker and Kubernetes allows developers to package their
applications into containers and then use Kubernetes to deploy, scale, and manage those containers, making it easier to build, test, and deploy applications in a 
consistent and repeatable way.
