# INC-005 — Utilisateur ne reçoit plus ses e-mails
Contexte

Un utilisateur signale qu'il ne reçoit plus de nouveaux e-mails dans sa messagerie Outlook.

Symptômes
Aucun nouvel e-mail reçu
Outlook affiche "Connecté" mais aucune synchronisation
Les autres utilisateurs reçoivent correctement leurs messages
Des expéditeurs signalent que les messages ont bien été envoyés
Diagnostic
Vérification de la connexion Outlook

Vérifier l'état de connexion dans Outlook :

Outlook -> Envoyer/Recevoir

Contrôler :

Outlook connecté au serveur
Aucun mode hors connexion activé
Vérification de la boîte aux lettres

Contrôler :

Espace de stockage disponible
Présence de règles de messagerie

Exemple :

Fichier -> Outils -> Gestion des règles
Test via Outlook Web Access

Se connecter à la messagerie web.

Exemple :

https://mail.entreprise.local

Vérifier :

Réception des nouveaux messages
Présence des messages attendus
Vérification des dossiers de messagerie

Contrôler :

Courrier indésirable
Archivage
Dossiers personnels
Cause probable
Boîte aux lettres saturée
Règle Outlook déplaçant les messages
Problème de synchronisation Outlook
Incident temporaire du serveur de messagerie
Résolution
Réinitialisation de la synchronisation Outlook

Fermer Outlook puis exécuter :

outlook.exe /resetfolders
Vérification des règles
Désactiver temporairement les règles suspectes
Tester la réception d'un nouveau message
Contrôle de l'espace disponible
Supprimer ou archiver les anciens messages
Vider les éléments supprimés
Résultat
Réception des e-mails rétablie
Synchronisation Outlook fonctionnelle
Boîte aux lettres opérationnelle
Compétences démontrées
Support utilisateur
Microsoft Outlook
Messagerie d'entreprise
Diagnostic applicatif
Résolution d'incident
