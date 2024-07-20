+++
title = "Romain Dauby Technical Director, Architect, CTO"
+++

[Version française](https://cv.romaindauby.fr/fr/)

## About Me

{{< figure class="avatar" src="https://www.gravatar.com/avatar/586e9d363077c0a9572652c9f5a4fcf3" >}}

Software engineering leader with a passion for online systems. I have a rich background in b2b, e-commerce, and online services in the gaming industry. 

My approach to leadership is rooted in the servant-leader philosophy, prioritizing the empowerment of agile teams to develop robust and efficient systems that align with key business goals.

In my capacity as a "hands-on" architect, I possess technical expertise in designing and managing large-scale distributed systems, cloud infrastructure and DevSecOps practices. My focus also extends to ensuring high-quality observability and maintaining effective on-call operations, essential for system reliability and security.

On the hobbies side: former road and track cycling coach who swims, runs and hikes in the mountains, left to discover Canada in 2021.

## Professionnal experiences

### Technical Lead, SRE Department, Ubisoft

#### 06/2021 to today

##### Roles

Technical lead of the four SRE (Site Reliability Engineering) teams (34 software or site reliability engineers) within Ubisoft Online Services (800 employees, international context: Canada, France, Germany, Ukraine, Romania, China).

Missions of the SRE department: build products, services, tools and practices to observe, secure, connect, scale software and distributed systems. Technical scope of each team:
* Logging, database, API Management, ephemeral metrics.
* Monitoring, metrics, alerts, dashboards, incident management (onCall).
* Tracing, healthchecks, dependency graphs, frontend.
* Security tools, DevSecOps practices and pipelines, automation, FinOps.

##### Projects

* Responsible for the achievements, decisions and technical architectures of the SRE teams, our direct clients are the developers of other departments on the online platform and sometimes game productions
* Provide a technological vision over 3 years, involving senior engineers, managers and directors
* Building robust and scalable observability products, we unify our telemetry collection and ingestion into the OpenTelemetry project, with open-source contributions
  * crossplane/provider-aws
  * open-telemetry/opentelemetry-collector-contrib
  * prometheus/prometheus
* IDS for the cloud and hybrid network with on-premise + China and implementation of infra as code projects, managed by a group of transversal experts.
* Construction of tools to collect data then observe through dashboards the level of software security (local fuzzing, SAST), the stacklines (Trivy, SonarQube) with secret detection, and at runtime (AWS Security hub, in house SIEM, EDR)

##### Missions

Transversal leadership:
* Contribution to the establishment of the Tech Board of the Online Services organization (boss's boss's boss of SRE), 800 employees. Objective, to review the technical architectures in the design phase adhering to our guiding principles (a bit like the AWS Well-Architected framework).
* Technical community lead of the Platform Services department (boss's boss of SRE), 120 employees. Maintains a bridge for discussions and cross-functional contributions to the teams.
* Evaluate market solutions to use managed services, contact with external companies.
* Architecture Decision Record (ADR) for our development practices, code organization and contributions and inner sourcing.
* Relationship with internal Ubisoft departments and external suppliers of observability, hosting and security software.

##### Skills

* Platforms: Kubernetes, Vault, Gitlab, Crossplane, Prometheus, AlertManager, Thanos, Grafana, Tempo, Loki, Mimir, OpenTelemetry, OpenSearch, Elasticsearch, Fluentd.
* Hosting: AWS, AWS China and Ubisoft on-premises.
* Software development: Go.
* Infra as code: Terraform, Terragrunt and development of Kubernetes operators to manage cloud objects: toil reduction.

### Technical Lead (DevOps), Cdiscount

#### From 02/2019 to 05/2021

##### Roles

Technical lead within the Customer Experience IT Department (120 engineers) with the role of infrastructure technical manager (DevOps practices). Scope of management:
* Mobile applications, PC site and mobile site [www.cdiscount.com](https://www.cdiscount.com).
* Order tunnel: [order.cdiscount.com](https://order.cdiscount.com).
* Customer area: [clients.cdiscount.com](https://clients.cdiscount.com).
* Customer relationship management (teleconsulting, after purchase).

At the same time, I led an SRE (site reliability engineering) role on the Linux fleet, mainly for on-call duties.
Cdiscount production includes 5,000 physical servers distributed in 2 data centers in France, a CDN with 6 points of presence, and projects in the Azure cloud.

##### Projects

* Bridge knowledge from the Platform Team with my department (SRE embedded).
* Microservice architecture migration of the mobile site of the marathon mesos cluster on kubernetes (Java 8 -> 11, NodeJS 8 -> 12, Docker, Kubernetes, Prometheus, Elasticsearch).
* Complete automation of load testing in the application deployment cycle (Swagger codegen, jMeter, Azure DevOps).
* R&D and contribution: reverse-proxy capable of managing more than 30k redirection and rewriting rules with hot reloading of the configuration via API (OpenResty, lua, c++).
* Automate recurring work by developing programs in Go and Python.
* Describe technical architectures and manage infrastructure capacity planning.
* Maintain and improve CICD pipelines for java, .net core, NodeJs and Go projects.
* Creation of a reverse proxy cache backend and reverse proxy cache sidecar in order to absorb the load of the site's busy commercial periods.

##### Missions

* Training (+ webinars) for developers on Ops, Perf and DevSecOps aspects.
* Continuous performance and DevSecOps premises on projects: Java (8, 10, 11), .net core (2.1, 3.1), NodeJS (12, 14, 15): microservices architectures, kubernetes.
* Construction and optimization of CICD pipelines (as code) on Azure Devops and Jenkins.
* Azure cloud IaaS with Terraform.
* Development of “Ops” features such as observability, tracing logging metrics; features "Perf" ; debug.
* Troubleshooting production incidents across the entire architecture, from CloudProtect (Acorus Networks DDoS protection - Volterra - F5) to databases.
* DevOps profile recruitment (company level).
* L2 duty on the Linux fleet: system administration, global architecture debug. Technologies: CDN (Varnish Nginx BotDetection), Kubernetes clusters (formerly Mesos / Marathon), Ceph, Varnish, MongoDB, Cassandra, CouchBase, Elasticsearch, Prometheus (Thanos), RabbitMQ, Kafka, Mapr, MediaDelivery Platform.
* DevOps community manager (enterprise scale).

### Architect Engineer, Orange Business Services

#### From 07/2018 to 02/2019

Architectural Engineer at the Orange Applications for Business DSI (team of 30 employees).

##### Missions

Interconnect the tools of business departments and those of the IT department at the architecture level: Application, Data and Infrastructure: modeling.

Guarantee the consistency and automation of application construction from the developer's station to production between developers and operators. Ensure good harmony in complex projects including multiple stakeholders.

Training and skills development of engineers on the HR movement management product from the local Docker image to production servers, monitoring, scalability, security.

##### Skills
TOGAF, Git, Docker, VMware, Nginx, Debian, OWASP ZAP, jMeter, MySQL, SaltStack, PHP, Scrum, DDD, TDD, DAT

### Software Engineer, Orange Business Services (OAB)

#### From 08/2015 to 07/2018

#### Projects

* Implementation of the Purchasing process in the external collaborator management web service. Implementation of the management process (manager role) in this same department.
* Development of the common base for the industrialization of authorization management: IAM.
* Implementation of a correlation identifier generated from the first reverse proxy of the microservices architecture with implementation in shared libraries in order to transmit this identifier in the microservices layers. Visualization and correlation of logs in Kibana dashboards. Principle of tracing in application logs.
* Creation of the elastic stack on-premises. Industrialization with ADR (technical architecture documentation) for production. Work reviewed and approved by the senior systems engineer.
* Industrialization of our development pipeline via Dockerfile, docker-compose, unit tests, mock bdd for unit tests, integration tests, tests on mutation tests, SONAR analyses, ORM Doctrine, hexagonal architecture, DDD, CICD Jenkins and above all deployment management on environments via git branches, (Gitflow house fork) for the employee movement management project.

##### Missions

Production of tools, training and processes to improve the practices of developers and system administrators within the IS team made up of 12 employees.

Technical manager of the application for managing the movement of employees and external service providers.
Software development in a microservices architecture and cloud-native applications.

Continuing training for employees on my work. Force of proposal for project functionalities and sometimes aMOA on projects for the department.

##### Skills
Docker, PHP, MySQL, Nginx, Debian, Git, Jenkins, Sonar, Gitlab, Zend Framework, PHPUnit, Slim framework, Elasticsearch, Filebeat, Logstash, Grok, Kiban, Jira, DDD, TDD, DAT, Javascript, jQuery, Doctrine Framework, Bash

### Software Engineering study of Information Service (apprenticeship), Orange Business Services (OAB/MBS)

#### From 09/2013 to 07/2015

##### Projects

* Implementation of a database (modeling) then of a web service for managing employee movements.
* Development of functionalities in the company's internal web services
   * Intranet (PHP MySQL)
   * Billing (Java MySQL)
   * SSO (Shibboleth)
   * Jira custom workflows (Javascript)
* Training on Docker, DevOps, Jenkins and Nginx given internally

##### Missions

Start-up, from scratch, of the employee movement management project: software craftmanship practices applied. In-depth study of the HR profession, HRIS in business and demonstration of a technical, technological and human organization application. This project made it possible to free up 1.5 FTEs per year by automating HR personnel movement management processes. Gain in quality in information processing and allowed HR to focus on more important issues for staff, which are difficult to automate.

Strong increase in skills on DDD in PHP, Docker, Linux Debian, software security and system administration.

### System Administrator (apprenticeship), Orange Business Services (MBS)

#### From 06/2012 to 08/2013

##### Missions
Management, modification and improvement of the company's internal tools.

Administration of Debian and Ubuntu servers. Hosted bare metal or in VMware virtual machines.

PHP development on around ten different projects: Zend framework 1 and 2.

Intervention on HO level 3 incidents.

Writing guidelines on the team's Rest APIs and ways of naming routes, in which case to use HTTP verbs, objective of respecting the REST standard as best as possible and fixing the vocabulary on the less clear elements of the standard.

### Web Developer (internship), MDNT Creation

#### 3 months in 2011 and 2 months in 2012

##### Projects / Missions

Website development, mainly PHP and Javascript.

Creation of a Prestashop module to allow hosting several stores and several seller accounts within the same Prestashop site. Project name: Batzeko.

Development of several dynamic sites with creation of a mini framework / skeleton for a backoffice.

Small structure, we develop, put into production and monitor websites.

Development of an algorithm that allows text substitutions to be made in order to fool the Google robot at precise intervals and make it believe that the text is changing. Integration of this algorithm transparently so that the content editor only has to use certain tags.

## Certifications

Date | Nom | Autorité de certification | Référence
-----|-----|---------------------------|----------
02/2024 | PCA: Prometheus Certified Associate | The Linux Foundation | [LF-u9onu4yriz](https://www.credly.com/badges/d4a45a4b-6cf8-497d-a942-9fba1ddf5fbc)
08/2023 | AWS Certified Solutions Architect – Associate | Amazon Web Services | [SAA-C03](https://www.credly.com/badges/c6ca23ee-4e20-4058-a7da-7c18d658505a)
03/2022 | CKA: Certified Kubernetes Administrator | The Linux Foundation | [LF-6v8ll4ppaz](https://www.credly.com/badges/2d722eac-2e7c-42c3-9696-8f528ef1b230)
08/2021 | AWS Certified Cloud Practicioner | Amazon Web Services | [CLF-C02](https://www.credly.com/badges/3b29ad0a-9f36-4d74-8dfc-90e3bb7f6985)
01/2020 | Certified Ethical Hacker | EC-Council | [ECC0785624139](https://aspen.eccouncil.org/VerifyBadge?type=certification&a=Cf9l4Imb8Rwmmk8312qAA84bFpDndb6G23VB6JzSWjg=)
04/2018 | TOGAF 9 Certified | The Open Group | [f12a95be-c8eb-4af8-a074-1acac4a0fedf](https://www.credly.com/badges/f12a95be-c8eb-4af8-a074-1acac4a0fedf)
04/2018 | TOGAF 9 Foundation | The Open Group | [2ed9a9fa-95f3-4822-a1ca-7ba22ae6e17a](https://www.credly.com/badges/2ed9a9fa-95f3-4822-a1ca-7ba22ae6e17a)
06/2015 | Professionnal Scrum Master I | Scrum.org | [131790](https://www.scrum.org/user/131790)

## Education

Year | Diploma | Title | Mention | School
-----|---------|-------|---------|-------
2015 | Master’s Degree | IT and information system expert | Honors | [EPSI Bordeaux](https://www.epsi.fr/)
2013 | BSc | Network and Database System Administrator | Congratulations | EPSI Bordeaux
2012 | BTEC Higher National Diploma | Management Information Systems | Good | EPSI Bordeaux
2008 | High School Diploma in Sciences | Mathematics Speciality | | [Lycée Saint Joseph de Tivoli](https://tivoli-33.org/)

## Volunteering Experiences

### Track and Road cycling coach

#### From 10/2017 to today

Member of the office of [SAM Cyclisme](https://www.samcyclisme.com/en-savoir-plus/encadrement-98707) as communication manager and federal diploma club coach issued by the French Cycling Federation.
Organizational and logistical assistance on cycle racing, lottery, garage sale type events.
Association law 1901.

### President EPSI Student's office

#### From 10/2010 to 10/2012

Very enriching experience as president of an association under the 1901 law.
Team management, burden sharing, accounting, communication and cash management.
Organization and logistical management of several ski weekends with ~50 participants and sports weekends up to 250 participants spread across France.

## Top 3 Books

* [The Phoenix Project](https://itrevolution.com/the-phoenix-project/), IT Revolution, *by Gene Kim, Kevin Behr, and George Spafford*
* [The Staff Engineer's path](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/), O'Reilly, *by Tanya Reilly*
* [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/), Google, *edited by Betsy Beyer, Chris Jones, Jenifer Petoff & Niall Murphy*
