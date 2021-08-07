# DevOps-Tools-Engineer

## Objectives
### 701 Software Engineering
#### 701.1 Modern Software Development 
* Understand and design service based applications
* Understand common API concepts and standards
* Understand aspects of data storage, service status and session handling
* Design software to be run in containers
* Design software to be deployed to cloud services
* Awareness of risks in the migration and integration of monolithic legacy software
* Understand common application security risks and ways to mitigate them
* Understand the concept of agile software development
* Understand the concept of DevOps and its implications to software developers and operators

#### 701.2 Standard Components and Platforms for Software
* Features and concepts of object storage
* Features and concepts of relational and NoSQL databases
* Features and concepts of message brokers and message queues
* Features and concepts of big data services
* Features and concepts of application runtimes / PaaS
* Features and concepts of content delivery networks

#### 701.3 Source Code Management
* Understand Git concepts and repository structure
* Manage files within a Git repository
* Manage branches and tags
* Work with remote repositories and branches as well as submodules
* Merge files and branches
* Awareness of SVN and CVS, including concepts of centralized and distributed SCM solutions

#### 701.4 Continuous Integration and Continuous Delivery 
* Understand the concepts of Continuous Integration and Continuous Delivery
* Understand the components of a CI/CD pipeline, including builds, unit, integration and acceptance tests, artifact management, delivery and deployment
* Understand deployment best practices
* Understand the architecture and features of Jenkins, including Jenkins Plugins, Jenkins API, notifications and distributed builds
* Define and run jobs in Jenkins, including parameter handling
* Fingerprinting, artifacts and artifact repositories
* Understand how Jenkins models continuous delivery pipelines and implement a declarative continuous delivery pipeline in Jenkins
* Awareness of possible authentication and authorization models
* Understanding of the Pipeline Plugin
* Understand the features of important Jenkins modules such as Copy Artifact Plugin, Fingerprint Plugin, Docker Pipeline, Docker Build and Publish plugin, Git Plugin, Credentials Plugin
* Awareness of Artifactory and Nexus

### 702 Container Management
#### 702.1 Container Usage
* Understand the Docker architecture
* Use existing Docker images from a Docker registry
* Create Dockerfiles and build images from Dockerfiles
* Upload images to a Docker registry
* Operate and access Docker containers
* Connect container to Docker networks
* Use Docker volumes for shared and persistent container storage

#### 702.2 Container Deployment and Orchestration
* Understand the application model of Docker Compose
* Create and run Docker Compose Files (version 3 or later)
* Understand the architecture and functionality of Docker Swarm mode
* Run containers in a Docker Swarm, including the definition of services, stacks and the usage of secrets
* Understand the architecture and application model Kubernetes
* Define and manage a container-based application for Kubernetes, including the definition of Deployments, Services, ReplicaSets and Pods

#### 702.3 Container Infrastructure
* Use Docker Machine to setup a Docker host
* Understand Docker networking concepts, including overlay networks
* Create and manage Docker networks
* Understand Docker storage concepts
* Create and manage Docker volumes
* Awareness of Flocker and flannel
* Understand the concepts of service discovery
* Basic feature knowledge of CoreOS Container Linux, rkt and etcd
* Understand security risks of container virtualization and container images and how to mitigate them

### 703 Machine Deployment
##### 703.1 Virtual Machine Deployment
* Understand Vagrant architecture and concepts, including storage and networking
* Retrieve and use boxes from Atlas
* Create and run Vagrantfiles
* Access Vagrant virtual machines
* Share and synchronize folder between a Vagrant virtual machine and the host system
* Understand Vagrant provisioning, including File, Shell, Ansible and Docker
* Understand multi-machine setup

#### 703.2 Cloud Deployment
* Understanding the features and concepts of cloud-init, including user-data and initializing and configuring cloud-init
* Use cloud-init to create, resize and mount file systems, configure user accounts, including login credentials such as SSH keys and install software packages from the distribution’s repository
* Understand the features and implications of IaaS clouds and virtualization for a computing instance, such as snapshotting, pausing, cloning and resource limits.

#### 703.3 System Image Creation
* Understand the functionality and features of Packer
* Create and maintain template files
* Build images from template files using different builders

### 704 Configuration Management
#### 704.1 Ansible
* Understand the principles of automated system configuration and software installation
* Create and maintain inventory files
* Understand how Ansible interacts with remote systems
* Manage SSH login credentials for Ansible, including using unprivileged login accounts
* Create, maintain and run Ansible playbooks, including tasks, handlers, conditionals, loops and registers
* Set and use variables
* Maintain secrets using Ansible vaults
* Write Jinja2 templates, including using common filters, loops and conditionals
* Understand and use Ansible roles and install Ansible roles from Ansible Galaxy
* Understand and use important Ansible tasks, including file, copy, template, ini_file, lineinfile, patch, replace, user, group, command, shell, service, systemd, cron, apt, debconf, yum, git, and debug
* Awareness of dynamic inventory
* Awareness of Ansibles features for non-Linux systems
* Awareness of Ansible containers

#### 704.2 Other Configuration Management Tools
* Basic feature and architecture knowledge of Puppet.
* Basic feature and architecture knowledge of Chef.

### 705 Service Operations
#### 705.1 IT Operations and Monitoring
* Understand goals of IT operations and service provisioning, including nonfunctional properties such as availability, latency, responsiveness
* Understand and identify metrics and indicators to monitor and measure the technical functionality of a service
* Understand and identify metrics and indicators to monitor and measure the logical functionality of a service
* Understand the architecture of Prometheus, including Exporters, Pushgateway, Alertmanager and Grafana
* Monitor containers and microservices using Prometheus
* Understand the principles of IT attacks against IT infrastructure
* Understand the principles of the most important ways to protect IT infrastructure
* Understand core IT infrastructure components and their role in deployment

#### 705.2 Log Management and Analysis
* Understand how application and system logging works
* Understand the architecture and functionality of Logstash, including the lifecycle of a log message and Logstash plugins
* Understand the architecture and functionality of Elasticsearch and Kibana in the context of log data management (Elastic Stack)
* Configure Logstash to collect, normalize, transform and ship log data
* Configure syslog and Filebeat to send log data to Logstash
* Configure Logstash to send email alerts
* Understand application support for log management
