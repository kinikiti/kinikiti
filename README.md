### Hi there 👋, I'm Kirill

> I'm a DevOps engineer based in **Belgium** with 25+ years of experience in the IT industry. 
My focus area for the past few years has been automated deployment of a data analytics platform in services in different cloud environments,
> but I'm also skilled in networking and streaming technologies.
> I am a result-oriented person with strong debugging and problem-solving skills.
> 

For the past few years,
my focus area has been on the automated deployment of data analytics platforms and services in various cloud environments.
In addition to this, I have expertise in networking and streaming technologies such as VoIP and video broadcasting.
As a results-oriented individual, I possess strong debugging and problem-solving skills.

# ☎️ Contact information

📧 kirill@16v.ru  
[<img align="left" alt="LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />](https://www.linkedin.com/in/kirill-nikitin-82954355)  [LinkedIn](https://www.linkedin.com/in/kirill-nikitin-82954355)  
[<img align="left" alt="Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />](https://www.instagram.com/kirill.m.nikitin)  [Instagram](https://www.instagram.com/kirill.m.nikitin)  
---

# 👩🏻‍💻 Work experience

## Platform engineer

**Freelance contractor**, Belgium – (Oct 2022 - present)*

Clients: Vlaamse Overheid, ST Engineering, Audi, Volkswagen, Deloitte, Spread GMBH

Main responsibilities:

Overall architectural system design for big data analytics platforms and systems based on RedHat OpenShift,
AWS and Azure implemented in hybrid environments with integration with various public Clouds.
Implementation of continuous delivery using Terraform, Ansible, Puppet and GitOps tools such as ArgoCD.

*Argenx*  
  
Building IaaC implementation of Azure Kubernetes using Terraform.
This is shared multi-tenant AKS cluster with different RBAC roles per project and tenant, with NIS2 security measures 
in places. Full cluster autoscaling was implemented using Karpenter.

*Vlaamse overheid.* 

Big data analytics platform based on the RedHat OpenShift initially in a hybrid environment,
including bare metal implementation with AWS integration.
Automation was implemented using Terraform and Kubernetes GitOps tooling.

I was responsible for the OKD cluster setup for the Development environment in AWS,
setting up core applications on the platform such as MinIO,
PostgreSQL, and Keycloak using ArgoCD, Helm, and Operator approach.
The setup was fully automated using GitHub Actions.

I design end implement monitoring and logging stack using Prometheus, Grafana and ELK.
Stack includes some custom components written by my using Python and Go.

Another main responsibility was connectivity management to all data sources,
external components, and repositories for the Production environment,
which doesn't have internet connectivity.

I was the single point of contact for all authentication questions and interactions with the government IDP,
as well as for OpenShift networking and performance questions.

*Volkswagen*

Operational platform on Azure AKS using SeaweedFS with Azure Blob for the S3 implementation and Azure Vault via CSI driver
for secret management.

I was responsible for the full design and implementation of GitHub CI/CD pipelines deploying three separate environments,
setting up all applications on  the platform such us MongoDB, Neo4j and Argo Workflows.

*Audi*

Operational platform on private OpenShift cluster using SeaweedFS for the S3 implementation and SOPS implementation for 
the secret management.

I was responsible for the full design and implementation of GitHub CI/CD pipelines deploying three separate environments,
setting up all applications on  the platform such us MongoDB, Neo4j and Argo Workflows.

*ST Engineering iDirect.*

Single point of contact for the team's resources in AWS and Azure. 

I was responsible for rebuilding the Azure Cloud part and migrating it between accounts, optimizing Azure resources,
and rebuilding Azure OpenShift (ARO) applications for a more generalized approach using Terraform and Terragrunt.
Additionally, I was responsible for upgrading and rebuilding several containers,
including migration to the latest base images, security hardening, and code upgrades using Jenkins pipelines.

*Deloitte*

Single point of contact for network security and connectivity,
including cloud-to-cloud and cloud-to-baremetal tunneling, IPSec security, and connectivity between private networks.
Key engineer for OpenShift cluster upgrade and maintenance, performing upgrades, cleanup,
and optimization for several OpenShift clusters used to serve client applications.
Third-line support engineer for platform-containerized applications like IBM Cloud Pak for Data.
I am involved in onboarding new clients to the analytical platforms.

## Chief Technology Officer

**Profit Group Kazakhstan**, Karaganda, Kazakhstan– (Jul 2013 - Nov 2022)*

The company provides a cloud platform for call centers in medical organizations. The platform includes several Linux-based servers for call distribution using Asterisk, several database servers using PostgreSQL, and a FreeBSD-based monitoring system. Currently, the platform handles 20,000 calls daily and about 10,000 SMS messages monthly for approximately 200 active customers.

Main responsibilities:

- Overall architectural system design.
- Continuous delivery of new features and services.
- Team lead for software team with task management, code review, and other common responsibilities.
- 2nd level support of the platform.
- Managing the 1st level support team.

Key achievements:

- Continuous real-time service delivery for a high-load platform with very limited hardware.
- Convergent platform for office telephony, call center with custom highly effective metrics, and notification service (audio, text to speech, and SMS notifications) for worldwide-based customers.
## Solution architect

**Deloitte**, *Brussels, Belgium – (Dec 2019 - Present)*

Key architect in several projects building a big data analytic platform in different clouds,
such as AWS, IBM Cloud and bare metal using RedHat Virtualization.
The platform includes about 60 virtual machines on the bare metal part and more than 100 EC2 instances in AWS and IBM Cloud
Responsible for whole virtualization on a bare metal platform,
responsible for all networking and security for all platform components.
Design and implement platform interconnections between different clouds.
Technology stack include Terraform for infrastructure components and puppet for state implementation.
CI/CD based on the GitLab or GitHub Actions in combinations with Terraform Cloud.

## Customer support engineer

**Synamedia Vividtec Europe**, *Kortrijk, Belgium– (Jan 2019 - Nov 2019)*

Customer support engineer for most of the Synamedia (former Cisco and NDS) Video technologies.
Support customer for such technologies as Videoscape TV, Videoscape Session Resource Manager and Cisco’s Explorer Controller, 
all Cisco's ROSA products (VSM, NMS, and EM), all Cisco's IRDs, and Cisco’s Digital Content Manager.
Support all Cloud DVR components with underlying virtualization and containerization infrastructure.
Participating on a Day 1 delivery project for one of the biggest telecom operators.
Leading and responsible for local Lab environment.
Managing local VMWare farm for internal usage. Supporting VMWare environment for our major customers.
Participating in several engineering projects

Key achievements:
Design and create an automation platform for support engineers for product logs analyzes based on SOLR search engine.
Migrate a knowledge database from Cisco to a Synamedia platform.
Design and deploy Technical Assistance Center Lab network and virtualization platform.

## Chief Technology Officer

**Profit Group Kazakhstan**, *Karaganda, Kazakhstan– (Jul 2013 - Present)*

Company provide Call Center cloud platform for medical organizations.
Platform includes several Linux-based servers for call distribution with Asterisk, several database servers with PostgreSQL and FreeBSD-based monitoring system.
At the present moment, the platform serves 20000 calls daily and about 10000 SMS messages monthly for about 60 active customers.

Main responsibilities:
Overall architectural system design.
Continuous delivery for new features and services.
Team Lead for a software team with task management, code review, and other common responsibilities.
Second level support of the platform.
Managing a first level support team.

Key achievements:
Continuous real-time service delivery for high load platform within very limited hardware.
Convergent platform for office telephony, call center with custom highly
effective metrics and notification service (audio, text to speech and SMS
notifications) for world-wide based customers

## Customer support engineer

**Cisco Systems bvba**, *Brussels, Belgium– (Jul 2016 - Jan 2019)*

Customer support engineer for most of the Cisco Video technologies.
Support Cisco's customer for such technologies as Videoscape TV, Videoscape Session Resource Manager, Cisco’s Explorer 
Controller, all Cisco's ROSA products (VSM, NMS, and EM), all Cisco's IRDs, and Cisco’s Digital Content Manager.
Main contributor for an automation platform for Cisco's Video products.
Leading and responsible for local Lab environment.
Managing local VMWare farm for internal usage. Supporting VMWare environment for our major customers.

Key achievements:
Becomes the only one person within Cisco Systems who can support all products within Cisco's Video product portfolio.
Create several web-based portals for different internal projects.
Create an internal automation platform from scratch to speedup failure diagnostic.
Design and create several tools (Python+PostgreSQL) for a different project to verify data and simplify delivery process.
Main stakeholder for several critical projects.

## Head of tech support department

**Electronics and Engineering**, *Moscow, Russia – (Mar 2014 - Jun 2016)*

Support for Russian Pension fund network and services.

Current contract includes more than 2800 sites in different regions equipped with Cisco, Huawei and Juniper network equipment, 
Cisco and Avaya phone systems (VoIP and traditional), Polycom and Huawei video conferencing.

Network engineers coordination and management

Second and third level support of all equipment

Network monitoring and audit of the current network

Fixing all VoIP problems

Fixing all video conference problems

Contractors Management

Chief consultant on technology for CEO end Executive Team of Russian Pension Fund

## IT Engineer

**Telecom Guard**, *Moscow, Russia – (Feb 2014 - Dec 2014)*

Working with one of the key customer - Aeroflot Russian Airlines.

2nd level support for company network and customers.

Audit of company network and network services.

Making of network modernization project, including network redesign, equipment and technology selection.

Network modernization project includes current network audit information, gathered from current infrastructure, description 
of all problems, new network design and technology description, equipment specification and pricing. In addition, I made few presentation materials for CEO and CTO.

## Project Manager

**private practice**, *Moscow, Russia – (Jul 2012 - Feb 2014)*

IT Consulting in different telecom spheres such as IP Telephony, IP networking, IP TV and Data Centers.

Key projects:

Data Center for Russian Railways

Second stage of DC building for Russian Railways. Second stage includes 20 racks for 350KVa of power. PUE about 1.3. 
Gathering requirements from customer. Choosing vendors, equipment and contractors for different systems. In addition, this project includes many corrections of existing data center.

Internet translation for "Rally Masters Show 2013"

Gathering requirements from Customer. Solution design and choosing contractors for implementation.

VoIP telephony for commercial bank

Overall system design. Choosing and configuring all the equipment for all branches.

VoIP system based on 3 Asterisk servers, about 700 customer phones (mainly AudioCodes and GrandStream), few VoIP gateways 
(GrandStream, AddPac, Mediant). In addition, head office was equipped with DECT phone system based on KIRK solution.

Support for all system for more than a year including relationships with providers and customers.

Call-center for a commercial bank

Overall system design, configuration and programming all interfaces. Design and implementation of a report and statistical systems for call-center.

---

# 🛠 Skills

## 💻 Technology

### Platform & Containers
* Red Hat OpenShift
* Kubernetes
* ROSA
* ARO
* KubeVirt
* Operators
* Podman
* Docker

### Cloud & Infrastructure
* AWS
* Azure
* On-premises
* Bare Metal
* Hybrid Cloud

### Infrastructure as Code
* Terraform
* Terragrunt
* Helm
* Argo CD
* GitOps
* Ansible

### CI/CD & DevEx
* Jenkins
* GitLab CI
* CI/CD Pipelines 
* Application Onboarding

### Networking & Security
* Kubernetes Networking
* RBAC
* TLS
* Cloud-to-Cloud Connectivity
* Cloud-to-Bare-Metal Tunneling
* Platform Security Hardening

### Observability & Operations
* Monitoring
* Logging
* Alerting
* Incident Response
* Day 2 Operations

### Languages & OS
* Linux (RHEL, Debian)
* Bash 
* Python 
* Go (basic)

---

## 🗣 Languages

### Russian
Native speaker 
### English
Proficient speaker 
### Dutch
Intermediate
---

# 📚 Education

## Master degree
Special machinery. Flight Dynamics and Movement Control, Graduate with honors  
1998 - 2004  
**Bauman Moscow State Technical University**

# 📖  Certification

* 2017	Red Hat certified system administrator in Red Hat OpenStack EX210
* 2021	IBM Cloud Pak for Data certified administrator
* 2021	AWS Solution Architect
* 2021 	Azure Fundamentals certification
* 2021	Azure AI Fundamentals certification
* 2022  Microsoft Azure Administrator Associate
* 2022	AWS Certified Advanced Networking – Specialty
* 2022	ITILv4 Foundation
* 2023  SAFe 5 Practitioner