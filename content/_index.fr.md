+++
title = "Romain Dauby Lead DevOps, Architect, CTO"
+++

[English version](https://cv.romaindauby.fr/en/)

## A propos de moi

{{< figure class="avatar" src="https://www.gravatar.com/avatar/586e9d363077c0a9572652c9f5a4fcf3" >}}

Passionné des technologies de l'information et avant tout des organisations humaines qui les opèrent, leader dans l'âme.
Expert des technologies  qui propulsent internet avec 8 années d'expériences, à l'aise sur de multiples domaines : architecture, génie logiciel, ingénierie de fiabilité, sécurité, performance, administration systèmes et réseaux ; à grande échelle.

Entraîneur en cyclisme sur route et piste et pratique la natation et la randonnée en montagne. 

## Expériences

### Leader Technique DevOps chez Cdiscount

#### 02/2019 à aujourd'hui

##### Missions

Lead DevOps au sein de la Direction IT Expérience Client (120 ingénieurs d'études) avec rôle de responsable infrastructure. Périmètre de la direction :
* applications mobiles, site PC et site mobile [www.cdiscount.com](https://www.cdiscount.com)
* tunnel de commandes: order.cdiscount.com
* espace client: clients.cdiscount.com
* gestion de la relation client (téléconsulting, après achat)

Ingénieur de fiabilité de site sur le parc Linux.
La production Cdiscount compte 5000 serveurs physiques répartis dans 2 datacentres en France, un CDN avec 6 points de présences, et des projets dans le cloud Azure.

##### Projets
* migration architecture microservice du site mobile du cluster mesos marathon sur kubernetes (Java 8 -> 11, NodeJS 8 -> 12, Docker, Kubernetes, Prometheus, Elasticsearch)
* automatisation complète des tirs de charges dans le cycle de déploiement des applications (Swagger codegen, jMeter, Azure DevOps)
* industrialisation d'un reverse-proxy capable de gérer + de 30k règles de redirections et de réécritures avec rechargement à chaud de la configuration via API (OpenResty, lua, c++)
* automatiser le travail récurrent en développant des programmes en Go et en Python
* décrire les architectures techniques et gérer le planning de capacité des infrastructures
* maintenir et améliorer les pipelines de CICD pour les projets java, .net core, NodeJs et Go.
* création d'un reverse proxy cache backend et reverse proxy cache sidecar afin d'absorber le load des périodes commerciales fortes du site

##### Compétences
* formation (+ webinars) des développeurs sur les aspects Ops, Perf et Sécu
* performance continue DevPerfOps et prémisses sécurité continue DevSecOps sur projets : Java (8, 10, 11), .net core (2.1, 3.1), NodeJS (12, 14, 15) : architectures microservices, kubernetes
* construction et optimisation de pipelines CICD (as code) sur Azure Devops et Jenkins
* IaaS cloud Azure avec Terraform
* développement de features "Ops" de type observability, tracing logging metrics ; features "Perf" ; debug
* troubleshooting incidents de production sur toute l'architecture, de CloudProtect (protection DDoS Acorus Networks - Volterra - F5) aux bases de données
* recrutement profil DevOps (échelle entreprise)
* astreinte N2 sur le parc Linux : administration système, debug architecture globale. Technologies : CDN (Varnish Nginx BotDetection), clusters Kubernetes (anciennement Mesos / Marathon), Ceph, Varnish, MongoDB, Cassandra, CouchBase, Elasticsearch, Prometheus (Thanos), RabbitMQ, Kafka, Mapr, MediaDelivery Platform.
* animateur communauté DevOps (échelle entreprise)

### Ingénieur Architecte chez Orange Business Services

#### 07/2018 au 02/2019

Promotion au poste d'ingénieur architecte à la DSI Orange Applications for Business (équipe de 30 collaborateurs).

##### Missions
Interconnecter les outils des directions métiers et ceux de la DSI au niveau des architectures : Application, Data et Infrastructure.

Garantir la cohérence et l'automatisation de la construction d'applications depuis le poste du développeur jusqu'en production entre les développeurs et opérateurs.
Assurer une bonne harmonie dans les projets complexes incluant de multiples acteurs.

Formation et montée en compétences des ingénieurs sur le produit de gestion des mouvements RH de l'image docker locale aux serveurs de production, monitoring, scalabilité, sécurité.

##### Compétences
DevOps, TOGAF, Git, Docker, VMware, Nginx, Debian, OWASP ZAP, MySQL, SaltStack, PHP, Scrum, DDD, TDD, DAT

### Ingénieur Développement et Production chez Orange Business Services

#### 08/2015 au 07/2018
  
##### Missions
Améliorer les pratiques des développeurs et des administrateurs système au sein de l'équipe SI composée de 12 collaborateurs.

Responsable technique de l'application de gestion des mouvements de collaborateurs et prestataires.
Développement de logiciels dans une architecture microservices.

Création d'un outil maison d'observabilité de type tracing. Avec un identifiant de corrélation généré à partir du premier reverse proxy de l'architecture microservices avec édition des librairies mutualisées (des microservices) afin de transmettre en intégrité cet identifiant. Avec corrélation des logs via des tableaux de bords kibana. Création de la elastic stack en local puis industrialisation + documentation d'architecture technique pour mise en production avec tampon de l'ingénieur système principal. (une sorte de MVP zipkin maison).

Industrialisation avancée via dockerfiles, docker-compose, tests unitaires, mock bdd pour TU, tests intégration, essai sur tests mutation, analyses SONAR, ORM, architecture hexagonale, DDD, CICD jenkins et surtout pilotage du déploiement sur les environnements via branches git, (fork maison Gitflow) pour le projet de gestion des mouvements de collaborateurs.

Formations régulières des ingénieurs sur mes travaux. Et force de proposition et parfois aMOA sur les projets de la DSI.

##### Compétences
Docker, PHP, MySQL, Nginx, Debian, Git, Jenkins, Sonar, Gitlab, Zend Framework, PHPUnit, Slim framework, Elasticsearch, Filebeat, Logstash, Grok, Kiban, Jira, DDD, TDD, DAT, Javascript, jQuery, Doctrine Framework, Bash

### Ingénieur d'Etudes du Système d'Information chez Orange Business Services

#### 09/2013 au 07/2015

##### Missions
Réalisation from scratch d'un projet web de gestion des mouvements de collaborateurs : software craftmanship.
Etude approfondie du métier RH, du SIRH en entreprise et démonstration d'une application technique, technologique et organisation humaine.

Ce projet a permis de dégager plusieurs ETP dans les tâches pénibles des paperasses RH pour leur faire gagner en qualité dans le traitement de l'information et se concentrer sur des problématiques autour de l'humain dans l'entreprise et non de problématiques logicielles ne répondant pas bien à leur besoin.

Forte montée en compétences sur DDD en PHP, Docker, Linux Debian, la sécurité logicielle et l'administration système.
Premières formations données sur Docker et les avancées techniques et technologiques des projets construits à des collaborateurs ingénieurs.

### Administrateur Systèmes et Réseaux chez Orange Business Services

#### 06/2012 au 08/2013

##### Missions
Gestion, modification et amélioration des outils internes de la société.

Administration de serveurs Debian et Ubuntu. Hébergés bare metal ou en machine virtuelles VMware.

Développement PHP sur une dizaine de projets différents : Zend framework 1 et 2.

Intervention sur des incidents HO niveau 3.

Ecriture de lignes directrices sur les API Rest de l'équipe et les façons de nommer les routes, dans quel cas utiliser les verbes HTTP, objectif respecter au mieux la norme REST et figer le vocabulaire sur les éléments moins clair du standard.

### Développeur web chez MDNT Creation

#### 3 mois en 2011 et 2 mois en 2012

##### Missions
Développement essentiellement PHP et Javascript sur des sites internet.

Création d'un module Prestashop afin de permettre d'héberger plusieurs boutiques et plusieurs comptes vendeur sur un même site prestashop projet Batzeko qui n'a malheureusement pas vu le jour étant prometteur.

Développement de plusieurs site dynamiques avec création d'un mini framework / skelette pour un backoffice. Software craftmanship.

Petite structure, nous développons, mettons en production et monitorons les sites internet.

Développement d'un algorithme qui permet de faire des substitutions de texte afin de tromper à intervalles précis le robot google et faire croire que le texte change. Intégration de cet algorithme de façon transparente pour que l'éditeur de contenu n'ai qu'à utiliser certaines balises. 

## Certifications

Date | Nom | Autorité de certification | Référence
-----|------|-------------------|----------
01/2020 | Certified Ethical Hacker | EC-Council | [ECC0785624139](https://aspen.eccouncil.org/VerifyBadge?&type=certification&a=Cf9l4Imb8Rwmmk8312qAA84bFpDndb6G23VB6JzSWjg=)
04/2018 | TOGAF 9 Certified | The Open Group | [f12a95be-c8eb-4af8-a074-1acac4a0fedf](https://www.youracclaim.com/badges/f12a95be-c8eb-4af8-a074-1acac4a0fedf/linked_in_profile)
04/2018 | TOGAF 9 Foundation | The Open Group | [2ed9a9fa-95f3-4822-a1ca-7ba22ae6e17a](https://www.youracclaim.com/badges/2ed9a9fa-95f3-4822-a1ca-7ba22ae6e17a/linked_in_profile)
06/2015 | Professionnal Scrum Master I | Scrum.org | [131790](https://www.scrum.org/user/131790)

## Formation

Année | Diplôme | Intitulé | Mention | Ecole
------|---------|----------|---------|-------
2015 | Maîtrise (Master 2) | Expert en Informatique et Système d'Information | Félicitations | [EPSI Bordeaux](https://www.epsi.fr/)
2013 | Maîtrise (Master 1) | Administrateur système réseau et base de données | Félicitations | EPSI Bordeaux
2012 | Baccalaureat | Informatique de Gestion, Spécialité Mathématiques | Bien | EPSI Bordeaux
2008 | Diplôme d'études collégiales | Scientifique, Spécialité Mathématiques | | [Lycée Saint Joseph de Tivoli](https://tivoli-33.org/)

## Expériences de bénévolat

### Entraîneur club cyclisme, route et piste

#### 10/2017 à aujourd'hui

Membre du bureau en tant que responsable communication et entraîneur club diplôme fédéral délivré par la Fédération Française de cyclisme.
Aide organisationnelle et logistique sur les événements de type course cycliste, loto, vide grenier.
Association loi 1901.

### Président BDE EPSI

#### 10/2010 au 10/2012

Expérience très enrichissante de présidence d'une association loi 1901 durant 2 années consécutives.
Management d'équipe, répartition des charges, gestion de la comptabilité, de la communication et de la trésorerie.
Organisation et gestion logistique de plusieurs weekends ski avec ~50 participants et weekends sportifs jusqu'à 250 participants répartis aux quatre coins de la France.

## Bibliographie

* [The DevOps Handbook](https://itrevolution.com/the-devops-handbook/), IT Revolution, *by Gene Kim, Jez Humble, Patrick Debois, and John Willis*
* [The Phoenix Project](https://itrevolution.com/the-phoenix-project/), IT Revolution, *by Gene Kim, Kevin Behr, and George Spafford*

