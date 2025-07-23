# Zabbix_supervision
TP sur Zabbix 

Ce document est un travail pratique (TP) portant sur Zabbix, une solution open source de supervision informatique. Il couvre à la fois les aspects théoriques (définitions, composants, concepts) et pratiques (installation, configuration, scénarios de surveillance).


**Objectifs du TP:**

**Objectif 1 : Installation et configuration de base**

  - Création de 2 machines virtuelles Debian 12 (Zabbix et Web)
  - Installation de PostgreSQL et de Zabbix 6.0 LTS sur la VM Zabbix
  - Configuration de la base de données, du serveur, de l’agent et de l’interface Web
  - Application des bonnes pratiques d’installation
    

**Objectif 2 : Exploration de l’interface Zabbix et ajout d’hôtes à surveiller**

- Ajout d’un hôte Web via l’agent Zabbix 2
- Vérification du bon fonctionnement d’Apache
- Interaction avec l’interface pour configurer et observer la supervision
  

**Objectif 3 : Configuration de scénarios de surveillance avancée**

- Création d’un scénario de supervision Web (First page, Login, Logout…)
- Utilisation des éléments personnalisés et déclencheurs (triggers) pour affiner les alertes


**Objectif 4 : Création de tableaux de bord**

**Mise en place de dashboards pour visualiser:**

- L’état des serveurs et services critiques
- Les performances réseau et système
- Les alertes, incidents, et les SLA
- Les conditions environnementales (température, humidité…)


**Contenu pédagogique et technique**
  
  Le TP aborde :

- La définition de la supervision dans un SI
- Le fonctionnement de Zabbix (serveur, agents, proxy, base de données, API…)
- Les types de métriques collectées
- La collecte de données avec ou sans agents
- Une comparaison avec des solutions concurrentes (Nagios, PRTG, Icinga…)
- Un lexique des termes essentiels
