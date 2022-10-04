
# Google Cloud Fundamentals: Core Infrastructure


## Quiz: Containers in the Cloud


### 1. What is a Kubernetes pod?

- [x] A group of containers
- [ ] A group of VMs
- [ ] A group of nodes
- [ ] A group of clusters


### 2. How do you keep your Kubernetes version updated in Google Kubernetes Engine?

- [x] The Google Kubernetes Engine team periodically performs automatic upgrades of your cluster to newer stable versions.
- [ ] You cannot update a running cluster. You need to create a copy of the cluster with the updated Kubernetes version.
- [ ] You need to stop your cluster and manually update the Kubernetes version in your cluster.
- [ ] You are required to set up a cron job to periodically check the Kubernetes version in your cluster.


### 3. How do containers access an operating system?

- [ ] Each container has its own instance of an operating system.
- [ ] Containers use a shared base operating system stored in a shared runtime layer.
- [ ] Containers use a shared base operating system stored in a Cloud Storage bucket.
- [x] Containers use a shared base operating system stored in a shared kernel layer.


### 4. Select two reasons for using containers to deploy applications. (Choose 2 responses.)

- [x] It creates consistency across development, testing, and production environments.
- [x] Migrating workloads is simpler.
- [ ] Allocating resources in which to run containers is not necessary.
- [ ] It provides tight coupling between applications and operating systems.


### 5. What is a Kubernetes cluster?

- [x] A group of machines where Kubernetes can schedule workloads.
- [ ] A group of pods that manage the administration of a Kubernetes application.
- [ ] A group of containers that provide high availability for applications.


###6. Anthos provides a rich set of tools for monitoring and maintaining the consistency of your applications across which of the following locations?

- [ ] Applications hosted on-premises only.
- [x] Applications hosted on-premises, in the cloud, or in multiple clouds.
- [ ] Applications hosted with multiple cloud providers only.
- [ ] Applications hosted with one cloud provider only.


###6. Where do the resources used to build Google Kubernetes Engine clusters come from?

- [x] Compute Engine
- [ ] Cloud Storage
- [ ] Bare metal servers
- [ ] App Engine
