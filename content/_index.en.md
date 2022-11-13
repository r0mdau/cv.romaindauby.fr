+++
title = "Romain Dauby Tech Lead, Architect, CTO"
+++

[Version française](https://cv.romaindauby.fr/fr/)

## About Me

{{< figure class="avatar" src="https://www.gravatar.com/avatar/586e9d363077c0a9572652c9f5a4fcf3" >}}

Passionate about online information technologies, distributed sustems and the human organizations that operate them.

With my 9 years of professional experience, I have acquired expertise in web technologies, comfortable in multiple fields: architecture, software engineering, reliability engineering, distributed systems, security, performance, system and network administration. My ability to take a step back allowed me to develop strong skills in managing complex projects, managing software development teams, managing budgets and managing products.

My hobbies: former road and track cycling coach and enjoys swimming, running and mountain hiking.

## Professionnal experiences

### Technical Lead at Ubisoft

#### 06/2021 to today

##### Missions
Technical lead of the five SRE teams within Ubisoft Online Services (34 software engineers / site reliability). Our mission is to build products, technologies and practices to observe, secure, connect, scale software and distributed systems. Technical perimeters of each team:
* logging, database, API Management
* monitoring, metrics, alerts, dashboards, onCall
* tracing, healthchecks, dependency graphs, frontend, incident management
* blue team, dev security tools, DevSecOps, automation
* green team, FinOps

##### Projects
* responsible for the achievements, decisions and technical architectures of the SRE teams, our direct customers are the developers of the other departments on the online platform and sometimes game productions
* give a technological vision over 3 years, involving senior engineers, managers and directors
* CTO community champion for Platform Services leadership
* recovery of the technical scope of the architectures in place allowing to observe the distributed systems of the teams (ECS, EKS, on-prem k8s / VM)
* creation of the architecture committee, takeover of the community of experts
* building observability products, we unify our telemetry behind the OpenTelemetry project, with open-source contributions
* creation of an expert community for the cloud and hybrid network with on-premise + China and implementation of infra as code projects
* construction of tools to collect data then observe through dashboards the level of security of software (local fuzzing, SAST), stacklines (Trivy, SonarQube) with detection of secrets, and at runtime (AWS Security hub, in house SIEM, EDR)
* evaluate market solutions for using managed services

##### Skills
* software development in Go
* decision architecture document for our development practices, organization of code and contributions, inner sourcing
* platforms: Kubernetes, Prometheus, AlertManager, Thanos, Grafana, Tempo, Loki, Mimir, OpenTelemetry, OpenSearch, Elasticsearch, Fluentd
* AWS, AWS China and Ubisoft on-premises hosting
* infra as code Terraform, Terragrunt and development of kubernetes operators to manage cloud objects: reduction of the web
* relationship with observability software vendors

### Technical Lead (DevOps) at Cdiscount

#### From 02/2019 to 05/2021

##### Missions
Technical Lead (DevOps practices) within the Customer Experience IT Department (120 software engineers) with the role of infrastructure technical manager. Management scope:
* mobile applications, PC site and mobile site [www.cdiscount.com](https://www.cdiscount.com)
* order tunnel: order.cdiscount.com
* customer area: customers.cdiscount.com
* customer relationship management (teleconsulting, after purchase)

I also combined a site reliability engineering role on the Linux estate.
Cdiscount production has 5,000 physical servers distributed in 2 data centers in France, a CDN with 6 points of presence, and projects in the Azure cloud.

##### Projects
* microservice architecture migration of the mobile site of the mesos marathon cluster on kubernetes (Java 8 -> 11, NodeJS 8 -> 12, Docker, Kubernetes, Prometheus, Elasticsearch)
* full automation of load tests in application deployment cycle (Swagger codegen, jMeter, Azure DevOps)
* R&D reverse-proxy capable of managing more than 30k redirect and rewrite rules with hot reloading of the configuration via API (OpenResty, lua, c++)
* automate recurring work by developing programs in Go and Python
* describe technical architectures and manage infrastructure capacity planning
* maintain and improve CICD pipelines for java, .net core, NodeJs and Go projects.
* creation of a reverse proxy cache backend and reverse proxy cache sidecar in order to absorb the load of the strong commercial periods of the site

##### Skills
* training (+ webinars) for developers on Ops, Perf and DevSecOps aspects
* continuous performance and DevSecOps premises on projects: Java (8, 10, 11), .net core (2.1, 3.1), NodeJS (12, 14, 15): microservices architectures, kubernetes
* building and optimizing CICD pipelines (as code) on Azure Devops and Jenkins
* Azure cloud IaaS with Terraform
* development of "Ops" features such as observability, tracing logging metrics; features "Perf"; debug
* troubleshooting production incidents on all architecture, from CloudProtect (DDoS protection Acorus Networks - Volterra - F5) to databases
* DevOps profile recruitment (enterprise scale)
* N2 on-call duty on the Linux fleet: system administration, global architecture debug. Technologies: CDN (Varnish Nginx BotDetection), Kubernetes clusters (formerly Mesos / Marathon), Ceph, Varnish, MongoDB, Cassandra, CouchBase, Elasticsearch, Prometheus (Thanos), RabbitMQ, Kafka, Mapr, MediaDelivery Platform.
* DevOps community manager (enterprise scale)


### Architect Engineer at Orange Business Services

#### From 07/2018 to 02/2019

Architect engineer at the Orange Applications for Business IT intern department (team of 30 employees).

##### Missions
Interconnect the tools of the business departments and those of the IT department at the architectural levels : Application, Data and Infrastructure.

Guarantee the consistency and automation of the construction of applications from the developer desktop to production between developers and operators.
Ensure good harmony in complex projects including multiple actors.

Training and skills development of engineers on the HR movement management product from the local docker image to production servers, monitoring, scalability, security.

##### Skills
TOGAF, Git, Docker, VMware, Nginx, Debian, OWASP ZAP, jMeter, MySQL, SaltStack, PHP, Scrum, DDD, TDD, DAT

### Development and production engineer at Orange Business Services

#### From 08/2015 to 07/2018

##### Missions
Improve the practices of developers and system administrators within the SI team of 12 employees.

Technical manager of the movement management application for employees and service providers.
Software development in a microservices architecture.

Creation of an in-house tracing tool. With a correlation identifier generated from the first reverse proxy of the microservices architecture with editing of the shared libraries (microservices) in order to transmit this identifier in integrity. With correlation of logs via kibana dashboards. Creation of the elastic stack locally then industrialization + technical architecture documentation for production with stamp from the main system engineer (a kind of Zipkin first alpha release).

Advanced industrialization via Dockerfile, docker-compose, unit tests, bdd mock for TU, integration tests, test on mutation tests, Sonar analyzes, ORM, hexagonal architecture, DDD, CICD jenkins and especially piloting of the deployment on environments via git branches, (fork Gitflow in-house) for the employee movement management project.

Regular training of engineers on my work. And force of proposal and sometimes aMOA on ISD projects.

##### Skills
Docker, PHP, MySQL, Nginx, Debian, Git, Jenkins, Sonar, Gitlab, Zend Framework, PHPUnit, Slim framework, Elasticsearch, Filebeat, Logstash, Grok, Kiban, Jira, DDD, TDD, DAT, Javascript, jQuery, Doctrine Framework, Bash

### Engineering study of Information Service at Orange Business Services

#### From 09/2013 to 07/2015

##### Missions
Creation from scratch of a web project for managing employee movements : software craftmanship. In-depth study of the HR profession, HRIS in business and demonstration of a technical, technological and human organization application. This project made it possible to free several FTEs in the arduous tasks of HR paperwork to improve their quality in the processing of information and to focus on issues around people in the company and not on software issues that do not meet well for their needs.

Strong skills development on DDD in PHP, Docker, Linux Debian, software security and system administration.

First training sessions given on Docker and technical and technological advances in projects built to engineers.

### System Administrator at Orange Business Services

#### From 06/2012 to 08/2013

##### Missions
Management, modification and improvement of the company's internal tools.

Administration of Debian and Ubuntu servers. Hosted bare metal or in a VMware virtual machine.

PHP development on ten different projects: Zend framework 1 and 2.

Intervention on HO level 3 incidents.

Writing guidelines on APIs Rest of the team and ways of naming routes, in which case use HTTP verbs, aim to better respect the REST standard and freeze the vocabulary on less clear elements of the standard.

### Web Developer at MDNT Creation

#### 3 months in 2011 and 2 months in 2012

##### Missions
Developments mainly in PHP and Javascript on websites.

Creation of a Prestashop module to allow the hosting of several shops and several seller accounts on the same prestashop site Batzeko project which unfortunately did not see the light of day being promising.

Development of several dynamic websites with creation of a mini framework / skeleton for a backoffice.
Software craftmanship.

Small structure, we develop, put into production and monitor websites.

Development of an algorithm which allows to make text substitutions in order to deceive the google robot at precise intervals and make believe that the text changes. Integration of this algorithm transparently so that the content editor only has to use certain tags.

## Certifications

Date | Name | Issuing authority | Reference
-----|------|-------------------|----------
03/2022 | CKA: Certified Kubernetes Administrator | Linux Foundation | [LF-6v8ll4ppaz](https://www.credly.com/badges/2d722eac-2e7c-42c3-9696-8f528ef1b230)
08/2021 | AWS Certified Cloud Practicioner | Amazon Web Services | [aws certified](https://www.credly.com/badges/3b29ad0a-9f36-4d74-8dfc-90e3bb7f6985)
01/2020 | Certified Ethical Hacker | EC-Council | [ECC0785624139](https://aspen.eccouncil.org/VerifyBadge?&type=certification&a=Cf9l4Imb8Rwmmk8312qAA84bFpDndb6G23VB6JzSWjg=)
04/2018 | TOGAF 9 Certified | The Open Group | [f12a95be-c8eb-4af8-a074-1acac4a0fedf](https://www.youracclaim.com/badges/f12a95be-c8eb-4af8-a074-1acac4a0fedf/linked_in_profile)
04/2018 | TOGAF 9 Foundation | The Open Group | [2ed9a9fa-95f3-4822-a1ca-7ba22ae6e17a](https://www.youracclaim.com/badges/2ed9a9fa-95f3-4822-a1ca-7ba22ae6e17a/linked_in_profile)
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
