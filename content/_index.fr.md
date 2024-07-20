+++
title = "Romain Dauby Directeur technique, Architecte, CTO"
+++

[English version](https://cv.romaindauby.fr/en/)

## A propos de moi

{{< figure class="avatar" src="https://www.gravatar.com/avatar/586e9d363077c0a9572652c9f5a4fcf3" >}}

Leader en génie logiciel passionné par les systèmes en ligne. J'ai une riche expérience dans le b2b, le commerce électronique et les services en ligne dans l'industrie du jeu.

Mon approche du leadership est ancrée dans la philosophie du leader-serviteur, donnant la priorité à l'autonomisation des équipes agiles pour développer des systèmes robustes et efficaces qui s'alignent sur les objectifs commerciaux clés.

En ma qualité d'architecte "hands-on", je possède une expertise technique dans la conception et la gestion de systèmes distribués à grande échelle, d'infrastructures cloud et de pratiques DevSecOps. Mon objectif s'étend également à garantir une observabilité de haute qualité et à maintenir des opérations d'astreinte efficaces, essentielles à la fiabilité et à la sécurité du système.

Côté loisirs : ancien entraîneur de cyclisme sur route et sur piste qui nage, court et randonne en montagne, parti découvrir le Canada en 2021.

## Expériences

### Lead Technique, Département SRE, Ubisoft

#### 06/2021 à aujourd'hui

##### Rôles

Responsable technique des quatres équipes SRE (Site Reliability Engineering) (34 ingénieurs logiciels ou fiabilité de site) au sein d'Ubisoft Online Services (800 employés, contexte international: Canada, France, Allemagne, Ukraine, Roumanie, Chine).

Missions du département SRE: bâtir des produits, services, outils et des pratiques pour observer, sécuriser, connecter, mettre à l'échelle les logiciels et les systèmes distribués. Périmètres techniques de chaque équipe :
* Logging, base de données, API Management, métriques éphémères.
* Monitoring, métriques, alertes, dashboards, gestion d'incidents (onCall).
* Tracing, healthchecks, graphes des dépendances, frontend.
* Outils de sécurité, pratiques et pipelines DevSecOps, automatisation, FinOps.

##### Projets

* Responsable des réalisations, décisions et architectures techniques des équipes SRE, nos clients directs sont les développeurs des autres départements sur la plateforme online et parfois les productions de jeux
* Donner une vision technnologique sur 3 ans, impliquant des ingénieurs séniors, des gestionnaires et des directeurs
* Construction de produits d'observabilité robustes et scalables, nous unifions notre collection et ingestion de télémétrie dans le projet OpenTelemetry, avec des contributions open-source
  * crossplane/provider-aws
  * open-telemetry/opentelemetry-collector-contrib
  * prometheus/prometheus
* IDS pour le réseau dans le cloud et hybride avec on-premise + Chine et mise en place de projets infra as code, géré par un groupe d'experts transverse.
* Construction d'outils pour collecter les données puis observer à travers des tableaux de bords le niveau de sécurité des logiciels (local fuzzing, SAST), les pilelines (Trivy, SonarQube) avec détection des secrets, et au runtime (AWS Security hub, in house SIEM, EDR)

##### Missions

Leadership transversal:
* Contribution pour la mise en place du Tech Board de l'organization Online Services (n+2 dep SRE), 800 employés. Objectif, revoir les architectures techniques en phase de design adhérent à nos principes conducteurs (un peu comme le cadre de travail AWS Well-Architected).
* Lead communauté technique de la direction Platform Services (n+1 dep SRE), 120 employés. Maintient un pont de discussions et contributions transverses aux équipes.
* Évaluer les solutions du marché pour utiliser des services managés, contact avec les entreprises externes.
* Document d'architecture de décision (ADR) pour nos pratiques de développement, d'organisation du code et des contributions et inner sourcing.
* Relation avec les départements internes Ubisoft et fournisseurs externes de logiciels d'observabilité, d'hébergement et de sécurité.

##### Compétences

* Plateformes: Kubernetes, Vault, Gitlab, Crossplane, Prometheus, AlertManager, Thanos, Grafana, Tempo, Loki, Mimir, OpenTelemetry, OpenSearch, Elasticsearch, Fluentd.
* Hébergement: AWS, AWS China et Ubisoft on-premises.
* Développement logiciel: Go.
* Infra as code: Terraform, Terragrunt et développement d'opérateurs kubernetes pour manager les objets du cloud : réduction du toil.


### Lead Technique (DevOps),  Cdiscount

#### 02/2019 au 05/2021

##### Rôles

Leader Technique au sein de la Direction IT Expérience Client (120 ingénieurs d'études) avec rôle de responsable technique infrastructure (pratiques DevOps). Périmètre de la direction :
* Applications mobiles, site PC et site mobile [www.cdiscount.com](https://www.cdiscount.com).
* Tunnel de commandes: [order.cdiscount.com](https://order.cdiscount.com).
* Espace client: [clients.cdiscount.com](https://clients.cdiscount.com).
* Gestion de la relation client (téléconsulting, après achat).

En parallèle, j'ai mené un rôle de SRE (ingénierie de fiabilité de site) sur le parc Linux, essentiellement pour les astreintes.
La production Cdiscount compte 5000 serveurs physiques répartis dans 2 datacentres en France, un CDN avec 6 points de présences, et des projets dans le cloud Azure.

##### Projets

* Relier les connaissances de l'équipe Plateforme avec mon département (SRE intégré).
* Migration architecture microservice du site mobile du cluster mesos marathon sur kubernetes (Java 8 -> 11, NodeJS 8 -> 12, Docker, Kubernetes, Prometheus, Elasticsearch).
* Automatisation complète des tests de charges dans le cycle de déploiement des applications (Swagger codegen, jMeter, Azure DevOps).
* R&D et contribution: reverse-proxy capable de gérer + de 30k règles de redirections et de réécritures avec rechargement à chaud de la configuration via API (OpenResty, lua, c++).
* Automatiser le travail récurrent en développant des programmes en Go et en Python.
* Décrire les architectures techniques et gérer le planning de capacité des infrastructures.
* Maintenir et améliorer les pipelines de CICD pour les projets java, .net core, NodeJs et Go.
* Création d'un reverse proxy cache backend et reverse proxy cache sidecar afin d'absorber le load des périodes commerciales fortes du site.

##### Missions

* Formation (+ webinars) des développeurs sur les aspects Ops, Perf et DevSecOps.
* Performance continue et prémisses DevSecOps sur projets : Java (8, 10, 11), .net core (2.1, 3.1), NodeJS (12, 14, 15) : architectures microservices, kubernetes.
* Construction et optimisation de pipelines CICD (as code) sur Azure Devops et Jenkins.
* IaaS cloud Azure avec Terraform.
* Développement de features "Ops" de type observability, tracing logging metrics ; features "Perf" ; debug.
* Troubleshooting incidents de production sur toute l'architecture, de CloudProtect (protection DDoS Acorus Networks - Volterra - F5) aux bases de données.
* Recrutement profil DevOps (échelle entreprise).
* Astreinte N2 sur le parc Linux : administration système, debug architecture globale. Technologies : CDN (Varnish Nginx BotDetection), clusters Kubernetes (anciennement Mesos / Marathon), Ceph, Varnish, MongoDB, Cassandra, CouchBase, Elasticsearch, Prometheus (Thanos), RabbitMQ, Kafka, Mapr, MediaDelivery Platform.
* Gestionnaire communauté DevOps (échelle entreprise).

### Ingénieur Architecte, Orange Business Services

#### 07/2018 au 02/2019

Ingénieur Architecte à la DSI Orange Applications for Business (équipe de 30 collaborateurs).

##### Missions
Interconnecter les outils des directions métiers et ceux de la DSI au niveau des architectures : Application, Data et Infrastructure : modélisation.

Garantir la cohérence et l'automatisation de la construction d'applications depuis le poste du développeur jusqu'en production entre les développeurs et opérateurs.
Assurer une bonne harmonie dans les projets complexes incluant de multiples acteurs.

Formation et montée en compétences des ingénieurs sur le produit de gestion des mouvements RH de l'image docker locale aux serveurs de production, monitoring, scalabilité, sécurité.

##### Compétences
DevOps, TOGAF, Git, Docker, VMware, Nginx, Debian, OWASP ZAP, jMeter, MySQL, SaltStack, PHP, Scrum, DDD, TDD, DAT

### Ingénieur Développement et Production, Orange Business Services (OAB)

#### 08/2015 au 07/2018

#### Projets

* Implémentation du processus Achat dans le service web de gestion des collaborateurs externes. Implémentation du processus de gestion (rôle manager) dans ce même service.
* Développement du socle commun de l'industrialisation de la gestion des habilitations: IAM.
* Mise en place d'un identifiant de corrélation généré à partir du premier reverse proxy de l'architecture microservices avec implémentation dans les librairies partagées afin de transmettre cet identifiant dans les couches de microservices. Visualisation et corrélation des logs dans des tableaux de bords Kibana. Principe du tracing dans des logs applicatifs.
* Création de la elastic stack on-premises. Industrialisation avec DAT (documentation d'architecture technique) pour mise en production. Travaux revus et approuvés par l'ingénieur systèmes principal.
* Industrialisation de notre pipeline de développement via Dockerfile, docker-compose, tests unitaires, mock bdd pour tests unitaires, tests intégration, essais sur tests de mutation, analyses SONAR, ORM Doctrine, architecture hexagonale, DDD, CICD jenkins et surtout pilotage du déploiement sur les environnements via branches git, (fork maison Gitflow) pour le projet de gestion des mouvements de collaborateurs.

##### Missions

Production d'outils, de formations et de processus pour améliorer les pratiques des développeurs et des administrateurs système au sein de l'équipe SI composée de 12 collaborateurs.

Responsable technique de l'application de gestion des mouvements de collaborateurs et prestataires externes.
Développement de logiciels dans une architecture microservices et applications cloud natives.

Formations continues des collaborateurs sur mes travaux. Force de proposition pour les fonctionalités des projets et parfois aMOA sur les projets de la DSI.

##### Compétences
Docker, PHP, MySQL, Nginx, Debian, Git, Jenkins, Sonar, Gitlab, Zend Framework, PHPUnit, Slim framework, Elasticsearch, Filebeat, Logstash, Grok, Kiban, Jira, DDD, TDD, DAT, Javascript, jQuery, Doctrine Framework, Bash, SSO, Shibboleth

### Ingénieur d'Etudes du Système d'Information (alternance), Orange Business Services (OAB/MBS)

#### 09/2013 au 07/2015

##### Projets

* Implémentation d'une base de données (modélisation) puis d'un service web de gestion des mouvements de collaborateurs.
* Développement de fonctionnalités dans les services web internes à l'entreprise
  * Intranet (PHP MySQL)
  * Facturation (Java MySQL)
  * SSO (Shibboleth)
  * Jira custom workflows (Javascript)
* Formations sur Docker, DevOps, Jenkins et Nginx données en interne

##### Missions

Démarrage, à partir de rien, du projet de gestion des mouvements de collaborateurs : pratiques de software craftmanship appliquées. Étude approfondie du métier RH, du SIRH en entreprise et démonstration d'une application technique, technologique et organisation humaine. Ce projet a permis de dégager 1.5 ETP par an en automatisant les processus de gestion des mouvements de personnel RH. Gain de qualité dans le traitement de l'information et a permis au RH de se concentrer sur des problématiques plus importante pour le personnel, qui sont peu automatisables.

Forte montée en compétences sur DDD en PHP, Docker, Linux Debian, la sécurité logicielle et l'administration système.

### Administrateur Systèmes et Réseaux (CDD puis alternance), Orange Business Services (MBS)

#### 06/2012 au 08/2013

##### Missions
Gestion, modification et amélioration des outils internes de la société.

Administration de serveurs Debian et Ubuntu. Hébergés bare metal ou en machine virtuelles VMware.

Développement PHP sur une dizaine de projets différents : Zend framework 1 et 2.

Intervention sur des incidents HO niveau 3.

Ecriture de lignes directrices sur les API Rest de l'équipe et les façons de nommer les routes, dans quel cas utiliser les verbes HTTP, objectif respecter au mieux la norme REST et figer le vocabulaire sur les éléments moins clair du standard.

### Développeur web chez MDNT Creation

#### 3 mois en 2011 et 2 mois en 2012

##### Projets / Missions
Développement de sites internet, essentiellement PHP et Javascript.

Création d'un module Prestashop afin de permettre d'héberger plusieurs boutiques et plusieurs comptes vendeur au sein d'un même site prestashop. Nom du projet: Batzeko.

Développement de plusieurs site dynamiques avec création d'un mini framework / skelette pour un backoffice.

Petite structure, nous développons, mettons en production et monitorons les sites internet.

Développement d'un algorithme qui permet de faire des substitutions de texte afin de tromper à intervalles précis le robot google et faire croire que le texte change. Intégration de cet algorithme de façon transparente pour que l'éditeur de contenu n'ai qu'à utiliser certaines balises.

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

## Formations

Année | Diplôme | Intitulé | Mention | Ecole
------|---------|----------|---------|-------
2015 | Maîtrise (Master 2) | Expert en Informatique et Système d'Information | Félicitations | [EPSI Bordeaux](https://www.epsi.fr/)
2013 | Maîtrise (Master 1) | Administrateur système réseau et base de données | Félicitations | EPSI Bordeaux
2012 | Baccalaureat | Informatique de Gestion, Spécialité Mathématiques | Bien | EPSI Bordeaux
2008 | Diplôme d'études collégiales | Scientifique, Spécialité Mathématiques | | [Lycée Saint Joseph de Tivoli](https://tivoli-33.org/)

## Expériences de bénévolat

### Entraîneur club cyclisme, route et piste

#### 10/2017 au 01/2022

Membre du bureau du [SAM Cyclisme](https://www.samcyclisme.com/en-savoir-plus/encadrement-98707) en tant que responsable communication et entraîneur club diplôme fédéral délivré par la Fédération Française de cyclisme.
Aide organisationnelle et logistique sur les événements de type course cycliste, loto, vide grenier.
Association loi 1901.

### Président BDE EPSI

#### 10/2010 au 10/2012

Expérience très enrichissante de présidence d'une association loi 1901 durant 2 années consécutives.
Management d'équipe, répartition des charges, gestion de la comptabilité, de la communication et de la trésorerie.
Organisation et gestion logistique de plusieurs weekends ski avec ~50 participants et weekends sportifs jusqu'à 250 participants répartis aux quatre coins de la France.

## Mon Top 3 livres

* [The Phoenix Project](https://itrevolution.com/the-phoenix-project/), IT Revolution, *by Gene Kim, Kevin Behr, and George Spafford*
* [The Staff Engineer's path](https://www.oreilly.com/library/view/the-staff-engineers/9781098118723/), O'Reilly, *by Tanya Reilly*
* [Site Reliability Engineering](https://sre.google/sre-book/table-of-contents/), Google, *edited by Betsy Beyer, Chris Jones, Jenifer Petoff & Niall Murphy*

