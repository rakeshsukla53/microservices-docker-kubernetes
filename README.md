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

# What's is a container and virtual machine

A VM will get physical resources like RAM, CPU, Network cards, etc and
“slice and dice” them into virtual resources. It then provides the
virtual resources on top of a hypervisor as smaller Virtual Machines
that look and feel like the normal physical computer where you can
then install a guest Operating System.

Docker “slices and dices” Operating System resources and not the
physical resources into what they prefer to call containers.

Containers are basically slicing the operating system resources:
https://medium.com/backticks-tildes/how-to-dockerize-a-django-application-a42df0cb0a99

Kubernetes cheatsheet - https://kubernetes.io/docs/reference/kubectl/cheatsheet/

# what is a dockerfile ?

Dockerfiles contain step by step instructions for creating docker images
