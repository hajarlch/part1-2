# part1-2
****************Part1 :How To Build a Node.js Application withDocker *******
Dans la partie 1, on a  crée une image d'application pour un site Web statique qui utilise
le framework Express et Bootstrap. Apres on a  construit un conteneur en utilisant cette image
et le pousser vers Docker Hub pour une utilisation future. Enfin, on a extrait  l'image stockée de
notre dépôt Docker Hub et construire un autre conteneur.


*****************Part3: Containerizing a Node.js Application for Development With Docker Compose *******
Le resultat de cette partie e une application d'information  les requins qui fonctionne
sur des conteneurs Docker  (fonctionne avec Node et MongoDBsur).
On a  crée deux conteneurs un pour l'application Node
et un autre pour la base de données MongoDB avec Docker Compose. 
notre configuration fera ce qui suit :
- Synchroniser le code de l'application sur l'hôte avec le code dans le conteneur pour
faciliter les changements pendant le développement.
- S'assurer que les modifications apportées au code de l'application fonctionnent sans redémarrage.
- Créer une base de données protégée par un utilisateur et un mot de passe pour les données de l'application.
- Faites persister ces données.

