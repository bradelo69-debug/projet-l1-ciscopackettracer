# projet-l1-ciscopackettracer
Projet final réalisé en première année de licence informatique ( lire le fichier README pour plus d'info )
Ce projet consiste en la conception et la simulation d'une infrastructure de maison connectée (Smart Home) à l'aide de Cisco Packet Tracer.

L'objectif est de mettre en place un environnement dans lequel différents équipements domestiques et objets connectés peuvent communiquer au sein d'un même réseau. Le projet intègre également des éléments liés à la gestion de l'énergie, notamment un panneau solaire et une batterie de stockage.

La simulation permet d'étudier la connexion, la configuration et les interactions entre les différents composants d'un système IoT domestique.

	Objectifs

Les principaux objectifs du projet sont les suivants :

concevoir l'architecture réseau d'une maison connectée ;
connecter différents équipements IoT ( correspond aux appareils d'une maison connectée ) à une infrastructure réseau ;
configurer les équipements nécessaires à leur communication ;
simuler le fonctionnement d'équipements domestiques connectés ;
intégrer un système élémentaire de production et de stockage d'énergie ;
accéder aux équipement via la tablette, grâce à l'adresse Ip+P du Home gateaway.

	Archtecture
L'infrastructure repose sur un Home Gateway servant de point central pour les équipements connectés. Celui-ci est relié au réseau via un câble modem.

Une tablette est également présente dans l'environnement afin de permettre l'interaction avec les équipements IoT.

Le système comprend notamment :

un Home Gateway ;
une tablette ;
plusieurs équipements IoT ;
un panneau solaire ;
une batterie

La maison intègre plusieurs dispositifs permettant de simuler différentes fonctions domestiques :

Équipement	        Fonction
Smart Lamp	        Gestion de l'éclairage
Smoke Detector	        Détection de fumée
Temperature Monitor	Surveillance de la température
Smart Door	        Gestion d'une porte
Garage Door	        Gestion de l'accès au garage
Smart Fan	        Ventilation
Appliance	        Contrôle d'un appareil électrique
Lawn Sprinkler	        Gestion de l'arrosage
MCU	                Contrôle de dispositifs IoT

Ces équipements permettent de représenter différents usages d'un réseau domestique connecté.

	Gestion de l'énergie

Le projet intègre également un système simplifié de production et de stockage d'énergie.

Le panneau solaire permet de simuler la production d'électricité tandis que la batterie assure son stockage. Cette partie permet de représenter l'interaction entre la production énergétique et les équipements électriques de la maison.

Cette architecture pourrait notamment servir de base à une étude ultérieure de la consommation énergétique et à l'optimisation de l'utilisation des ressources.

	Réseau et communication

Les différents équipements sont intégrés à l'infrastructure réseau de la maison afin de permettre leur communication.

Cisco Packet Tracer permet de visualiser et de tester les échanges entre les différents composants. Le mode Simulation peut notamment être utilisé pour observer les paquets et analyser leur circulation dans le réseau.

	Technologies et notions utilisées
Cisco Packet Tracer
IoT 
Smart Home
Réseau local (LAN)
TCP/IP
IPv4
Home Gateway
Microcontroller Unit (MCU)
Simulation réseau

Pour consulter le projet :

Installer Cisco Packet Tracer.
Ouvrir le fichier smart-home.pkt.
Examiner la topologie et la configuration des différents équipements.
Utiliser les modes Realtime et Simulation pour tester le fonctionnement du réseau.
Observer les échanges entre les équipements connectés.
Infos utiles : adresse du Homegateaway à entrer sur la tablette -> 192.168.25.1 

	Compétences travaillées
conception d'une architecture réseau ;
configuration d'équipements réseau ;
adressage et communication IP ;
intégration d'objets IoT ;
utilisation d'un microcontrôleur ;
analyse des échanges réseau ;
simulation d'un système domestique connecté ;

	Auteur

Brad Musandji--Elo Asong à l'aide des enseignements de l'Université Lumière Lyon 2

Projet réalisé avec Cisco Packet Tracer

