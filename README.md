# microservices-docker-kubernetes
Docker and Kubernetes stuff 


# What is microservices ?

Microservices is a just an architectural design which means that your application
should be `modular` `easy to deploy` and `scale independently`.

Modern application consists of multiple binaries and need to be updated on demand.

# What is a docker ?

A package consists of application and all it's dependencies to run. Through docker api
you can run your package. It will be easy to create, distribute and run.

Native operating system good at installing, starting and stopping an application.

# What is a container ?

Technology that makes it easy to run and distribute applications
across different environments.

    - Independent Packages
    - Namespace Isolation

Containers are similar to virtual machine but much lighter weight

# What is kubernetes ?

Pod is the smallest unit of deployment in Kubernetes configuration
Pod contains container
All the containers run inside the pod in Kubernetes
Pods represent a logical application
    - one or more containers
Pods provide shared namespace
one ip per pod



Kubernetes cheatsheet - https://kubernetes.io/docs/reference/kubectl/cheatsheet/

# what is a dockerfile ?

Dockerfiles contain step by step instructions for creating docker images
