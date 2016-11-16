# resto
Projet en équipe Webforce3

Cahier des charges : 
Présentation du projet

Créer un site internet pour un restaurant (maquette en annexe). Le projet sera divisé en deux grandes parties, le FRONT et le BACK. Le FRONT sera ce que l’internaute verra lors de son arrivé sur le site. Le BACK quant à lui, permettra au client final de modifier aisément son site internet.

*Structure du projet FRONT* <br>
Le FRONT sera composé de 3 pages :
- une page d’accueil : 
  - photo de couverture :
  - 3 à 5 recettes 
  - une page listant les recettes comprenant un moteur de recherche 
  - une page contenant un formulaire de contact L’ensemble des pages auront la même structure et la même apparence.

*Structure du projet BACK* <br>
Le BACK sera sécurisé par identifiant et mot de passe et accessible depuis un sous-dossier /admin/ Il permettra de : 
  - Gérer les coordonnées du restaurant 
  - Modifier la photo de couverture 
  - Gérer les recettes (titre + contenu + photo + date & heure + id auteur) 
  - Traiter les réponses du formulaire de contact en marquant comme lu une réponse (par défaut, non lu) 
  - Créer un nouvel utilisateur 

Pour les utilisateurs, deux rôles seront présents : 
  - L’administrateur : 
    - Pourra intervenir sur l’ensemble du site 
  - L’éditeur : 
    - Pourra uniquement publier des recettes
Note : Chaque utilisateur pourra modifier son mot de passe

*Obligations* <br>
La base de données contiendra au moins une table pour les utilisateurs, une table pour les recettes. Les coordonnées du restaurant et la photo de couverture seront stockées dans une même et unique table (options). Les noms et colonnes des tables seront en anglais.

*Divers* <br>
Le code se doit d’être lisible, indenté et compréhensible pour vos collaborateurs.
Le projet doit être finalisé ce vendredi à 17h00.
Le projet sera versionné sur Github afin de pouvoir collaborer en équipe facilement et ainsi d’éviter d’écraser par mégarde le travail de vos collègues.

*Bonus : Mettre un slider jQuery administrable en remplacement de la photo de couverture. Attention, ne perdez pas de temps inutile avec les bonus*
