---
layout: default
---
![photo Quentin Perez](https://cv.archives-ouvertes.fr/photo/762591/large?v=1616602965)

**Associate Professor of Software Engineering at [INSA Rennes](https://www.insa-rennes.fr/index.html) - Research in the 
[DiverSE Team](https://www.diverse-team.fr/), IRISA, Inria, Univ Rennes, CNRS - France**

# About me

Hello :wave: , I'm associate professor of Software Engineering at [INSA Rennes](https://www.insa-rennes.fr/index.html). 
I'm doing research in the [DiverSE Team](https://www.diverse-team.fr/) in the IRISA/Inria lab at Rennes in France. 

My research interests are the following:
- Software Energy Consumption and Green IT :seedling:
- Empirical Software Engineering
- Software Metrics and Quality
- AI for Software Quality

Currently, I'm working on the energy consumption of the software supply chain (CI/CD and build managers) used in the 
DevOps loop. These systems are interesting to study due to their massive, automatic, and frequent use in DevOps. 
Supply chains use various tools to build software, and their high configurability gives them a special status in the 
software world. My research consists of finding solutions to reduce the consumption of DevOps tools and providing 
developers with a perception and evaluation of the software energy consumption in the DevOps loop. 
To achieve this, I employed a mining software engineering approach to collect and evaluate tools used in the DevOps 
world at a large scale. 

# Contact and social networks
- Email : quentin.perez at_ irisa.fr :email:
- [Google Scholar](https://scholar.google.com/citations?user=xZYkVhsAAAAJ&hl)
- [HAL](https://cv.archives-ouvertes.fr/quentin-perez) :newspaper:
- [ORCID](https://orcid.org/0000-0002-1534-4821) :scroll:
- [LinkedIn](https://www.linkedin.com/in/quentin-perez-93b832a4)
- [Github](https://github.com/qperez) :technologist:
- [Twitter](https://twitter.com/qperez19) :bird:

Rubrique :
<!-- TOC -->
* [Diplômes](#diplômes)
* [Publications](#publications)
  * [Journal Paper](#journal-paper)
  * [Conférences Internationales](#conférences-internationales)
    * [Regular Papers](#regular-papers)
    * [Short Papers](#short-papers)
  * [Workshop Papers](#workshop-papers)
  * [Conférences Francophones](#conférences-francophones)
* [Posters](#posters)
* [Activités d'enseignement](#activités-denseignement)
  * [Tableau récapitulatif des enseignements dispensés](#tableau-récapitulatif-des-enseignements-dispensés)
  * [Création de cours et TP](#création-de-cours-et-tp)
* [Responsabilités et activités associatives](#responsabilités-et-activités-associatives)
* [Expérience professionnelle](#expérience-professionnelle)
* [Qualification](#qualification)
* [Certification](#certification)
* [Comité de programme](#comité-de-programme)
* [Sub-Reviewer](#sub-reviewer)
<!-- TOC -->
***
# Diplômes

## 2021 | Doctorat en Informatique - : EuroMov Digital Health In Motion, IMT Mines Alès, France

**Sujet : Gestion des contributions architecturales dans les projets logiciels : Métriques, analyses empiriques et apprentissage machine**

**Directeur·e·s de thèse :** [Christelle Urtado](https://cv.hal.science/christelleurtado) et [Sylvain Vauttier](https://sylvainvauttier.wp.imt.fr/)

**Jury :**

|                    |         |                             |             |
|--------------------|---------|-----------------------------|-------------|
| Xavier BLANC       | PR      | LABRI, Univ. de Bordeaux    | Rapporteur  |
| Anne ETIEN         | PR      | CRIStAL, Univ. de Lille     | Rapportrice |
| Antoine BEUGNARD   | PR      | Lab-STICC, IMT Atlantique   | Président   |
| Chouki TIBERMACINE | MCF HDR | LIRMM, Univ. de Montpellier | Examinateur |
| Christelle URTADO  | MA HDR  | EuroMov DHM, IMT Mines Alès | Directrice  |
| Sylvain VAUTTIER   | MA HDR  | EuroMov DHM, IMT Mines Alès | Directeur   |

**Slides de la soutenance** : [https://drive.google.com/file/d/1oBxeE1bw01A86U2IDtWAiRvIaICsX7fJ/view?usp=sharing](https://drive.google.com/file/d/1oBxeE1bw01A86U2IDtWAiRvIaICsX7fJ/view?usp=sharing)

**Vidéo de la soutance** : [https://www.youtube.com/watch?v=WN5B3RrTwRE](https://www.youtube.com/watch?v=WN5B3RrTwRE)

**Résumé :** En génie logiciel, l’outillage des processus de développement est aujourd’hui indispensable à la gestion qualitative des projets et peut couvrir différentes phases : conception, codage ou maintenance. Cet outillage protéiforme regroupe les mesures appelées métriques, les systèmes automatisés de production de code et les systèmes d’aide à la décision, prédictifs ou non. Le champ d’application de ces derniers est large : détection de bad smells, classification de tickets, etc. Dans cette thèse, nous nous intéressons à la production de métriques portant sur la conduite des projets logiciels en s’appuyant sur les contributions au code source et plus particulièrement à l’architecture runtime des applications. Nous utilisons également des méta-données liées à l’historique du projet et à son développement.La première problématique étudiée concerne la classification de tickets logiciels décrivant des bogues. Nous entraînons un réseau de neurones sur un jeu de données reconnu par la communauté scientifique et nous optimisons ses hyper-paramètres à l’aide d’un algorithme génétique. De cette manière, nous obtenons des performances de classification supérieures à l’état de l’art. Ces performances permettent d’envisager l’intégration de notre classifieur dans des outils de gestion de projets ou dans un assistant à la rédaction de tickets.La deuxième question abordée est le turn-over des développeurs contribuant au développement de l’architecture logicielle. La détection des développeurs contribuant de manière majeure ou mineure a déjà été formulée et des métriques dédiées proposées. Cependant, les approches existantes ne se focalisent pas spécifiquement sur le développement de l’architecture. C’est pourquoi nous avons créé un modèle formel ainsi qu’une métrique de contribution au code de l’architecture. Nous validons cette métrique de manière empirique puis nous proposons une analyse des différentes catégories de développeurs extraites par notre métrique. Les résultats mettent en lumière la présence de catégories de développeurs spécifiques dont un noyau de développeurs expérimentés contribuant de manière majeure au code de l’architecture durant toute la vie du projet.La détection des développeurs expérimentés ayant de potentielles connaissances en architectures est également un problème que nous étudions. Contrairement aux approches existantes, nous utilisons l’apprentissage supervisé pour apprendre des profils de développeurs expérimentés. Aucun jeu de données étiquetées n’étant disponible dans la littérature scientifique, nous avons créé un jeu de données dédié. Pour cela nous extrayons plusieurs centaines de développeurs issus de 17 projets open source. Nous calculons ensuite 23 métriques pour chacun des développeurs contribuant à ces projets. Enfin, nous étiquetons notre jeu de données manuellement en utilisant les réseaux sociaux professionnels ainsi que la documentation des projets. Nous entraînons ensuite un classifieur sur ce jeu de données et nous l’évaluons. Nos résultats montrent de bonnes performances sur la détection de profils de développeur expérimentés, ce qui permet d’envisager l’utilisation d’un tel outil pour faciliter le management des projets. Enfin, nous réalisons une étude par croisement des résultats obtenus via la métrique de contribution à l’architecture et ceux obtenus par la classification automatique des développeurs. Cette étude permet d’analyser le profil des développeurs expérimentés. Nous analysons également l’évolution des 23 métriques des développeurs durant leur passage d’inexpérimenté à expérimenté. Les résultats montrent qu’une grande part des développeurs expérimentés sont également des contributeurs majeurs à l’architecture et que le changement de catégorie d’un développeur est multifactoriel.Nous fournissons également une évaluation de la reproductibilité de nos travaux en utilisant des cadres méthodologiques définis pour les études en génie logiciel empirique et en apprentissage automatique. 

---
## 2018 | Master en Informatique - Université de Franche-Comté - UFR-Sciences et Techniques 

Master en Informatique obtenu à l'Université de Franche-Comté et effectué en alternance de 24 mois avec le [groupe Flowbird](https://www.linkedin.com/company/flowbird-group/), leader mondial dans les solutions dédiées au stationnement.

Spécialité : Ingénierie Systèmes et Logiciels.

Sujet de Master : Conception et développement d'un système d'information géographique dédié au stationnement. Sujet réalisé sous la direction de [Fabrice Bouquet](https://members.femto-st.fr/fbouquet/) (université) et Judicaël Bully (entreprise Flowbird)

Mention : Bien (major de promotion)

---
## 2016 | Licence Informatique - Université de Franche-Comté - UFR-Sciences et Techniques

---
## 2015 | DUT Informatique - Université de Franche-Comté - IUT Belfort-Montbéliard

---

# Publications

## Journal Paper

* Quentin Perez, Christelle Urtado, Sylvain Vauttier. Dataset of open-source software developers labeled by their experience level in the project and their associated software metrics. Data in Brief, 2023, 46, pp.108842.


## Conférences Internationales

Vous pouvez aussi retrouver mes publications sur mon [CV HAL](https://cv.archives-ouvertes.fr/quentin-perez).
 
### Regular Papers

#### Publications de rang A (CORE)
* Corentin Latappy, Quentin Perez, Thomas Degueule, Jean-Rémy Falleri ,Christelle Urtado, Sylvain Vauttier, Xavier Blanc, Cédric Teyton. MLinter: Learning Coding Practices from Examples-Dream or Reality? SANER 2023 - 30th IEEE International Conference on Software Analysis, Evolution and Reengineering, March 2023, Macao, China, Online (**CORE rang A**)

* Quentin Perez, Pierre-Antoine Jean, Christelle Urtado, Sylvain Vauttier. Bug or not bug? That is the question. ICPC 2021 - 29th IEEE/ACM International Conference on Program Comprehension, May 2021, Online, France. pp.47--58, Online (**CORE rang A**)

#### Publications de rang B (CORE)

*  Quentin Perez, Christelle Urtado, Sylvain Vauttier. Mining Experienced Developers in Open-source Projects. ENASE 2022 - 17th International Conference on Evaluation of Novel Approaches to Software Engineering, Apr 2022, Online, France. pp.443-452. (CORE rang B)

### Short Papers

#### Publications de rang B (CORE)

* Quentin Perez, Alexandre Le Borgne, Christelle Urtado, Sylvain Vauttier. Towards Profiling Runtime Architecture Code Contributors in Software Projects. ENASE 2021 - 16th International conference on Evaluation of Novel Approaches to Software Engineering, Apr 2021, Online, United States. (CORE rang B)
* Quentin Perez, Alexandre Le Borgne, Christelle Urtado, Sylvain Vauttier. An Empirical Study about Software Architecture Configuration Practices with the Java Spring Framework. SEKE: Software Engineering and Knowledge Engineering, Jul 2019, Lisbonne, Portugal. pp.465-468. (CORE rang B)

## Workshop Papers

* Gaëlic Bechu, Antoine Beugnard, Caroline Gl Cao, Quentin Perez, Christelle Urtado, Sylvain Vauttier. A software engineering point of view on digital twin architecture. ETFA 2022 - IEEE 27th International Conference on Emerging Technologies and Factory Automation, Sep 2022, Stuttgart, Germany. 

## Conférences Francophones

* Gaëlic Bechu, Antoine Beugnard, Caroline Gl Cao, Quentin Perez, Christelle Urtado, Sylvain Vauttier. Déploiement dirigé par les modèles de jumeaux numériques dans les environnements intelligents. HUT LaConf 2022 - L'interdisciplinarité au service des environnements intelligents, Nov 2022, Montpellier, France.

# Posters

* Alireza Asvadi, Gaëlic Bechu, Antoine Beugnard, Caroline G. L. Cao, Christophe Lohr, Quentin Perez, Christelle Urtado et Sylvain Vauttier. Model-driven deployment of Digital Twins for Smart Environments - The HUman at home projecT case study. Journées nationales du GDR GPL 2022, Jun 2022, Vannes, France. , 13, 2022, Actes des journées du GDR GPL 2022.

***

# Activités d'enseignement

J'ai exercé mes enseignements principalement à l'IMT Mines Alès de 2018 à 2022 mais aussi à l'Université de Montpellier en 2021 et 2022.

## Tableau récapitulatif des enseignements dispensés

| Statut    | Année       | Établissement | Public  | Niveau                                      | Matière                        | Volume Horaire  | Nature          | Responsabilités            | Supports | 
|-----------|-------------|---------------|---------|---------------------------------------------|--------------------------------|-----------------|-----------------|----------------------------|----------|
| Doctorant | 2018 – 2019 | IMT Mines Alès |         | L3 (1ère année ingé généraliste)            | Algorithmique et POO (Java)    | 13h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2018 – 2019 | IMT Mines Alès | INFRES  | L3 (1ère année ingé par apprentissage info) | Approche objets (UML)          | 15h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2018 – 2019 | IMT Mines Alès |         | M1 (2ème année ingé généraliste spé info)   | Projet GL                      | 16h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2018 – 2019 | IMT Mines Alès |         | M2 (3ème année ingé généraliste spé info)   | Étude Technique                | 10h             | Projet étudiant | Encadrement                |   | 
 | Doctorant | 2018 – 2019 | IMT Mines Alès |         | M1 (2ème année ingé généraliste spé info)   | Mission R&D                    | 20h             | Projet étudiant | Encadrement                |   | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès |         | M1 (2ème année ingé généraliste spé info)   | Programmation Orientée Objet   | 8h              | TP/TD           | Encadrement                |   | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès |         | M2 (3ème année ingé généraliste spé info)   | Qualité Logicielle             | 6h30            | Cours           | Création de cours          | https://www.slideshare.net/secret/GUfJLao8HZXZHk | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès |         | M2 (3ème année ingé généraliste spé info)   | Bonnes pratiques logicielles   | 10h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès |         | M1 (2ème année ingé généraliste spé info)   | Projet GL                      | 16h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès |         | L3 (1ère année ingé généraliste)            | Base de données relationnelles | 14h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès | INFRES  | L3 (1ère année ingé par apprentissage info) | Approche objets (UML)          | 15h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2019 – 2020 | IMT Mines Alès | INFRES  | L3 (1ère année ingé par apprentissage info) | Langages objets (Java)         | 11h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2020 – 2021 | IMT Mines Alès |         | L3 (1ère année ingé généraliste)            | Base de données relationnelles | 14h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2020 – 2021 | IMT Mines Alès | INFRES  | L3 (1ère année ingé par apprentissage info) | Approche objets (UML)          | 15h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2020 – 2021 | IMT Mines Alès | INFRES  | L3 (1ère année ingé par apprentissage info) | Langages objets (Java)         | 11h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2020 – 2021 | IMT Mines Alès |         | M2 (3ème année ingé généraliste spé info)   | Qualité Logicielle             | 6h30            | Cours           | Création de cours          | https://www.slideshare.net/secret/GUfJLao8HZXZHk | 
 | Doctorant | 2020 – 2021 | IMT Mines Alès |         | M1 (2ème année ingé généraliste spé info)   | Mission R&D                    | 20h             | Projet étudiant | Encadrement                |   | 
 | Doctorant | 2021 – 2022 | IMT Mines Alès |         | L3 (1ère année ingé généraliste)            | Base de données relationnelles | 14h             | TP/TD           | Encadrement                |   | 
 | Doctorant | 2021 – 2022 | Univ Montpellier |         | M2                                          | IA pour le GL                  | 6h              | TP/TD           | Création TP et encadrement | https://github.com/qperez/TP-Master-MTP-GL-IA4GL/ | 
 | Post-doc  | 2022 – 2023 | Univ Montpellier |         | M2                                          | IA pour le GL                  | 9h              | TP/TD           | Création TP et encadrement |   | 
 | Post-doc  | 2022 – 2023 | IMT Mines Alès |         | M2 (3ème année ingé généraliste spé info)   | Qualité Logicielle             | 9h30            | Cours           | Création de cours          |   | 

## Création de cours et TP

### IMT Mines Alès, 3ème année (M2) d'ingénieur généraliste (parcours Ingénierie Logicielle) - Qualité Logicielle
**6h30 en 2021 puis 9h30 en 2022.**

J'ai monté ce cours avec pour objectif d'apprendre aux étudiants les méthodes et les outils permettant un développement 
logiciel de manière industrielle. Dans ce cours sont abordées les notions de modularité, de construction et de 
packaging avec gestionnaire de construction (Maven). 
Une introduction aux différents niveaux/types de tests logiciels est donnée. Le concept d'intégration continue est 
également abordé. Sur la base de ce cours un TP a été créé pour permettre aux étudiants d'expérimenter le refactoring
avec Maven, la création de tests unitaires avec JUnit5, 
la rédaction de tests fonctionnels avec Cucumber ainsi que l'intégration continue à l'aide de GitHub et Travis CI.

Les étudiants travaillent sur la modélisation objet d'une machine à café polymorphique et composé de divers composants
(moulin, réservoir à eau/café, résistance, etc.). Ce projet sous Maven est buggé à dessein et la construction échoue.
Les étudiants ont pour object de corriger le build puis de refactorer le projet en créant un nouveau module Maven. Ils 
doivent ensuite implémenter quelques cas de test fonctionnels avec Cucumber et mettre en place une intégration
continue à l'aide Github Actions.

Le dépôt Github suivant contient le code du TP ainsi que les slides de cours créés pour ce dernier :
* [https://github.com/qperez/cours-IL-Maven-2022](https://github.com/qperez/cours-IL-Maven-2022)


### Université de Montpellier, Master Informatique M2 (parcours GL) - Intelligence Artificielle pour le Génie Logiciel
**6h en 2021 puis 9h en 2022.**

Ce TP a été monté afin d'offir aux étudiants en Master Informatique (parcours Génie Logiciel) de l'Université de 
Montpellier une ouverture sur l'utilisation de méthodes d'intelligence artificielle pour des problèmatiques GL. 
Ces TP s'inspirent de nos travaux de recherche. Dans une première partie du TP il est demandé aux étudiants de créer un 
prédicteur du nombre de développeurs expérimentés en fonction du nombre de lignes de code.
Une seconde partie de ce TP s'intéresse à la construction d'un classifieur de tickets de bogue via de l'apprentissage supervisé
et un corpus de tickets fourni. 

Ce TP permet aux étudiants de mettre en oeuvre des méthodes et outils acquis par ailleurs dans d'autre module sur 
un cadre applicatif GL. Ainsi, cela permet pédagogiquement de croiser les approches et les réflexions autour 
de thématiques liées à l'IA et au GL. 

Les deux parties du TP sont réalisés sous forme de Notebook Jupyter sur Google Colab afin de facilité l'installation et l'utilisation des outils
mais aussi pour guider au mieux les étudiants sur le workflow à mettre en œuvre.
* [TP1 Classification de développeurs et prédiction du nombre requis](https://colab.research.google.com/drive/1dkdA1rcTDjyyMPj07ICgyVOOND-kWjPv)
* [TP2 Classification de tickets](https://colab.research.google.com/drive/1eH9HSTJDrxr9wSOVnr-V9KlhTQMy5mGj)

---

# Responsabilités et activités associatives
### 2019-2021 | Représentant des doctorants en Informatique à l'[École Doctorale I2S](https://edi2s.umontpellier.fr/) 
### 2019-2021 | Représentant des doctorants au comité de pilotage du [Centre d’Enseignement et de Recherche en Informatique et Systèmes](https://www.mines-ales.fr/ecole/imt-mines-ales/les-centres-de-recherche-et-denseignement/ceris) (CERIS) (2019-2021)
### 2019-2021 | Représentant des doctorants au comité de l'unité de recherche [Euromov DHM](https://dhm.euromov.eu) (2019-2021)
### 2019-2020 | Trésorier de l'association des [Thésards de l'École des Mines d'Alès](https://www.linkedin.com/in/athema-mines-al%C3%A8s-13b2a113b/) (ATHEMA) (2019-2020)

# Expérience professionnelle

## Dec. 2021 - Dec 2022 | Chercheur post-doctorant à IMT Mines Alès, projet TwinCoBot financé par l'institut Carnot Télécom.

Projet d'essaimage financé par l'Institut Carnot Télécom sur les jumeaux numériques (Digital Twins) dans les contextes d'environnements connectés domotiques et l'industrie 4.0. Réalisation d'un méta-modèle générique à ces 2 cas d'usage ainsi que d'un démonstrateur de jumeau numérique d'appartement connecté en lien avec le projet HUman aT project (HUT). 

## Oct. 2018 - Dec. 2021 | Doctorant en Informatique à IMT Mines Alès

## Sept. 2018 - Oct. 2018 | Ingénieur développement logiciel - groupe Flowbird 

Mission d'intérim faisant suite à mon alternance au poste d'ingénieur informatique sur le projet web GIS
* Traduction de l'interface web à l'aide de jQuery i18n
* Création de pollers HTTP
* Refactoring architectural et création de modules par fonctionnalités avec Maven

##  Sept. 2016 - Sept. 2018 | Alternant Ingénieur développement logiciel - groupe Flowbird

Développement d'un système d'information géographique (SIG) web from Scratch avec le framework Spring et base de données PostGIS
* Front-end : Jquery, Google Maps API JS, HTML5/CSS3, JSON, Ajax
* Back-end : Java et framework Spring
* Base de données : PostGIS
* Ontologie des données : Schema.org et JSON-LD
* Livraison sous forme d'images Docker sur plate-forme Amazon Web Service Elastic Container Registery (AWS ECR)
* Tests et qualité logicielle :
  - Construction : Maven
  - Tests unitaires : JUnit
  - Tests fonctionnels : JUnit/ Cucumber
  - Intégration continue : Jenkins
  - Création d'environnements de test Dockerisés
  - Mécanismes d'healthchecks Docker et applicatifs (DB+Tomcat)

Missions annexes :
  - Maintenance applicative sur serveur cartographique Dataiku
  - Rédaction de documentations fonctionnelles à destinations des managers et ingénieurs d'affaires

# Qualification

Qualification aux fonctions de Maitre de Conférence, section 27 obtenue en 2022 : [https://www.galaxie.enseignementsup-recherche.gouv.fr/ensup/qualification/Resultats_2022/qualifies_MCF_2022.pdf](https://www.galaxie.enseignementsup-recherche.gouv.fr/ensup/qualification/Resultats_2022/qualifies_MCF_2022.pdf)

# Certification

## Testeur logiciel niveau fondation de l'International Software Testing Qualifications Board (ISTQB)
ID de certification : [57998](http://scr.istqb.org/?name=&number=57998)

***

# Comité de programme 

---
# Sub-Reviewer

## Conférences
* SEKE 2019 : 1 article 
* SEKE 2020 : 1 article
* SANER 2020 : 1 article
* ASE 2020 : 1 article

***