# Trailrunning
Projet de Trailrunning effectué en fin d'année de mon BTS SNIR. 

Présentation du projet

Le Trail est une course à pied qui se passe en général en montagne ou en forêt. Une société souhaite organiser cette course du 17 au 19 juin 2022. Pour cela, ils nous demandent de réaliser un site web, une application mobile, une application de gestion ainsi qu’une installation de caméras pour filmer la course : 
	Site Web :
Utilisateur non connecté :
			-    Page d’accueil
			-    Formulaire d’inscription
			-    Liste des courses sans accès aux vidéos ou flux vidéo live
Utilisateur connecté
Page d’accueil avec nom et prénom de l’utilisateur
Accès aux listes des courses et aux vidéos
Si la course est en cours : accès seulement au live avec classement
Si la course est terminée, accès à nos vidéos : accès seulement aux vidéos de l’utilisateur
Inscription aux courses
  Application mobile :
Utilisateur non connecté :
Page d’accueil avec formulaire d’ouverture de session (Création du compte sur le site Web).
Utilisateur connecté :
Page de sélection de la course où l’utilisateur est inscrit. 
L'utilisateur peut badger avec son téléphone (NFC) son départ, son arrivée et son passage aux deux étapes. 
Visualisation du chronomètre (temps écoulé depuis le départ).
A chaque étape affichage du classement
Visualisation des étapes déjà validées.
Affichage du rythme cardiaque du coureur.
En option : accéder comme sur le site web aux vidéos de l'utilisateur.

Application de gestion :
Création/édition d'une course :
Nom de la course.
Distance entre les étapes.
Nombre de coureurs maximum.
Chargement d’une carte décrivant le parcours.
Sélection d’une course pas encore commencée :
Pilotage de la course
Départ
Possibilité de badger à la place d'un utilisateur.
Visualiser en direct l'avancement d'un coureur.
Visualiser le classement provisoire.
Arrêt
Sélection d’une course terminée
Visualiser le résumé de la course.
Visualiser le classement de la course.
















Répartition des tâches

Pour répondre aux attentes de cette demande, nous nous sommes réparti les tâches de la manière suivante:
Elève N°1 :
Création d’un site web permettant au public d’avoir des informations sur le Trail running :
Utilisateur non connecté : accueil, création d’un compte, listes des courses (sans accès aux vidéos).
Utilisateur connecté : accueil personnalisé, accès aux listes des courses et aux vidéos, inscription aux courses.
Tests et validation du site web.

Elève N°2 :
Création d’une appli mobile permettant aux coureurs de gérer leurs courses :
Utilisateur non connecté : accueil, formulaire d’ouverture de session
Utilisateur connecté : sélection d’une course, validation des passages aux points d’étape, chronométrage, classement en temps réel, progression, rythme cardiaque
Tests et validation de l’appli réalisée.

Elève N°3 :
Installation de la partie stockage du serveur :
Banque de données sur Vmware avec disque en RAID
Mise en œuvre des caméras sur Raspberry
Mise en œuvre des flux multicast pour chaque Raspberry :
Connexion caméra <-> Raspberry <-> serveur
Mise en œuvre du système de création des vidéos personnalisées à la demande
Tests et validation des fonctionnalités mises en œuvre.




Elève N°4 :
Création d’une application de gestion de la course :
Création/édition d’une course : nom, distance entre étapes, nombre de coureurs, carte
Sélection d’une course pas encore commencée : déclenchement, validation d’étapes, visualisation de flux vidéo en direct, classement en temps réel, clôture de la course
Sélection d’une course terminée : visualisation du résumé et du classement de la course
Tests et validation des fonctionnalités de l’IHM réalisée.
Commun (tous les élèves) :
Conception du diagramme de déploiement du système
Implantation de la BDD sur le serveur
Mise en commun des solutions
Test finaux de fonctionnement de l’installation complète.
