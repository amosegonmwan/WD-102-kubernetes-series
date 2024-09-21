## Container Orchestration

**Container orchestration** is all about managing the life cycles of containers, especially in large, dynamic environments.

Container Orchestration can be used to perform a lot of tasks, some of them includes:

  - Provisioning and deployment of containers
  - Scaling up or removing containers to spread application load evenly
  - Movement of containers from one host to another if there is a shortage of resources
  - Load balancing of service discovery between containers
  - Health monitoring of containers and hosts

There are many container orchestration solutions which are available, some of the popular ones include:

 - **Docker Swarm**
 - **Kubernetes**
 - **Apache Mesos**
 - **Elastic Container  Service (AWS ECS)**

## How does container orchestration work?

Container orchestration uses **declarative programming**, meaning you define the desired output instead of describing the steps needed to make it happen. 
Developers write a **configuration file** that defines where container images are, how to establish and secure the network between containers, 
and provisions container storage and resources. Container orchestration tools use this file to achieve the requested end state automatically.

When you deploy a new container, the tool or platform automatically schedules your containers and finds the most appropriate host for them based on the 
predetermined constraints or requirements defined in the configuration file, such as CPU, memory, proximity to other hosts, or even metadata. 

Once the containers are running, container orchestration tools automate life cycle management and operational tasks based on the container definition file, including:
 - Provisioning and deployment
 - Scaling containers up or down and load balancing
 - Allocating resources between containers
 - Moving containers to another host to ensure availability if there’s a shortage of resources or an unexpected outage
 - Performance and health monitoring of the application
 - Allocating resources between containers
 - Service discovery

## Benefits of container orchestration.
One of the biggest benefits of container orchestration is that it simplifies operations. Automating tasks not only helps to minimize the effort and complexity of managing containerized apps, 
it also translates into many other advantages.
 - **Reliable application development** : development is faster and repeatable hence increase in velocity
 - **Scalability** : Scales based on changing workloads
 - **Enhanced security**: Allows you to manage security policies across platforms which helps reduce human errors that can lead to vulnerabilities.
 - **High availability** : If a container fails, it can be restarted or replaced automatically, helping to maintain availability and increased application uptime.
 - **Lower costs** : Platforms require less human capital and time, yielding additional cost savings.
 - **Better productivity** : Reduce repetitive tasks and remove the burden of installing, managing, and maintaining containers.  

## Types of container orchestration tools.

There are two types of container orchestration platforms: 
- **Self-built**
- **Managed**

**Self-built** container orchestrators give you complete control over **customization** and are typically built from scratch or leveraging an open source platform. 
However, self-built options also mean you take on the burden of managing and maintaining the platform.

**Managed** platform or a **Containers as a Service (CaaS)** is offered from cloud providers, such as Google, Microsoft, Amazon, or IBM. With managed container orchestration platforms or CaaS, 
the cloud provider is responsible for managing installation and operations. As a result, you can simply consume the capabilities and focus on running your containerized applications. 