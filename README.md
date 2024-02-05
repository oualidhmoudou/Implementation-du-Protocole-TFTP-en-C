# Implementation-du-Protocole-TFTP-en-C
Ce projet vise à implémenter, et à étendre, le protocole Trivial File Transfer Protocol (TFTP) en C, en se concentrant sur le contrôle de flux et la gestion des connexions réseau. TFTP est un protocole léger utilisé pour transférer des fichiers sur un réseau. Ce projet approfondira vos compétences en programmation réseau, en gestion de la perte de paquets, et en synchronisation dans un environnement multi-utilisateurs.
# Étape 1 : Programme Client TFTP
Fonctionnalités Clés :
Lecture de fichiers : Envoyer une requête de lecture (RRQ) au serveur et gérer la réception des données.
Écriture de fichiers : Envoyer une requête d'écriture (WRQ) et transmettre le fichier au serveur.
Gestion des erreurs : Traiter les erreurs comme la perte de paquets en implémentant des timeouts et des retransmissions.
