# Kubernetes
Kubernetes (K8s) is an open source project that was released by Google in June, 2014. 
Google launches 2 billion containers a week in their infrastructure and has been using container technology for over a decade. 
Originally they were building a system named Borg, and now Omega, to schedule their vast quantities of workloads across their ever-expanding data center footprint. 

Benefits of using KUBERNETES
Load balancing
Horizantial auto-scalling
App helth check
Rolling updates

Replication controllers
Replication controllers manage the lifecycle of pods. They insure a specified number of specific pods are running at any given time. They do this by creating or deleting pods as required. For this reason, it's recommended you use a replication controller even if you are creating a single pod.
Let’s create the replication controller for our previously used nginx pod.
Create the nginxrc.yaml file

