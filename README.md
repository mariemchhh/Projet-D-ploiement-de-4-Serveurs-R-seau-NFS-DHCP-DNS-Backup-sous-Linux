# Projet-D-ploiement-de-4-Serveurs-R-seau-NFS-DHCP-DNS-Backup-sous-Linux
Description du projet
Ce projet vise à configurer et déployer quatre serveurs essentiels pour la gestion et l’administration d’un réseau d’entreprise ou d’un environnement de test. Chaque serveur joue un rôle clé dans la fourniture de services réseau :

Serveur NFS (Network File System) – Fournit un partage de fichiers centralisé aux clients du réseau.
Serveur DHCP (Dynamic Host Configuration Protocol) – Attribue automatiquement des adresses IP et des paramètres réseau aux clients.
Serveur DNS (Domain Name System) – Résout les noms de domaine en adresses IP pour faciliter la communication sur le réseau.
Serveur de Backup – Sauvegarde et restaure les données critiques des autres serveurs et clients du réseau.
Objectifs
Automatiser la gestion des adresses IP grâce au serveur DHCP.
Faciliter le partage de fichiers avec un serveur NFS sécurisé.
Gérer la résolution des noms de domaine via un serveur DNS interne.
Assurer la sécurité des données grâce à un serveur de sauvegarde centralisé.
Vérifier l’interopérabilité entre les quatre serveurs pour garantir un réseau stable et performant.
Configuration et Déploiement
1️⃣ Serveur NFS – Partage de fichiers
Installation et configuration du service NFS.
Définition des répertoires partagés et des permissions d’accès.
Montage des partages NFS sur les clients.
2️⃣ Serveur DHCP – Attribution dynamique des adresses IP
Installation du service DHCP.
Définition des plages d’adresses IP et des paramètres réseau.
Tests avec des clients DHCP pour valider la configuration.
3️⃣ Serveur DNS – Résolution des noms de domaine
Installation et configuration d’un serveur DNS (BIND).
Création de zones directes et inverses.
Test de la résolution des noms avec nslookup et dig.
4️⃣ Serveur de Backup – Sauvegarde des données
Mise en place d’un serveur de sauvegarde avecrsync ou Bacula.
Programmation des tâches de sauvegarde automatique.
Vérification et restauration des sauvegardes.
Validation et Tests
Tester le DHCP : Vérifier que les clients reçoivent des adresses IP automatiquement.
Tester le NFS : Vérifier que les clients peuvent accéder aux fichiers partagés.
Tester le DNS : Vérifier la résolution des noms de domaine interne.
Tester la sauvegarde : Vérifier que les données sont bien sauvegardées et restaurées.
Ce projet fournit une base solide pour la gestion d’un réseau sécurisé et optimisé.
