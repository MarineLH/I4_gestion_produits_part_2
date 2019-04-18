# TP 1 - Solution Cloud - Issue #3

Accès Issues #1 et #2 :
-
https://github.com/MarineLH/I4_gestion_produits_part_1

Sujet : 
-

Optimiser l'intégration dans un orchestrateur de containers
A terme, cette application sera déployée sur un orchestrateur de container (Kubernetes ou Docker Swarm).

Effectuez les modifications nécessaires de manière à ce que cette application puisse s'intégrer le plus facilement possible dans ces orchestrateurs en permettant notamment une mise à l'échelle horizontale (ajout de plusieurs serveurs pour chaque service).


**Fonctionnalités :**

Les 3 fichiers de déploiements permettent l'intégration plus facile sur un orchestrateur de containers, ici **Kubernetes**, 
des containers suivants :
- Application Web
- Base de données
- Serveur Minio
