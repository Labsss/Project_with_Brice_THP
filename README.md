# Projet final : plate-forme pour gérer l'idéation

## Problématiques
Dans le processus d'innovation tel qu'il existe, il y a grosso modo 4 étapes dans le pipeline de l'innovation:
1. Proposer et rechercher des idées qui répondent à un irritant ou problème
2. Analyser la proposition pour voir si cela est faisable
3. Faire un protype pour voir les premiers retours clients
4. Développer et généralisr

# Description

## Principe du projet

La plate-forme doit permettre de :
 * un visiteur pour consulter la liste des proposition d'idées
 * un utilisateur (visiteur connecté) pourra proposer son idée
 * une propal aura une catégorie du type : RH, Développement Durable, CE, Asso, ou ajouter une catégorie absente
 * un utilisateur pourra commenter une idée pendant une durée terminée pour l'améliorer ou faire une critique constructive
 * les commentaires ne pourront pas être anonymes mais les propals d'idées oui
 * un administrateur pour voir toutes les propositions et faire le CRUD
 * A chaque action sur une propal, un mail d'information doit être fait
 * l'administrateur peut changer le statut de propal:
   * soit accordé pour une étude approfondie et réalisation d'un prototype
   * soit en recyclage, l'idée est intéressante mais il faut la travailler encore
   * soit annuler car ce n'est pas ou plus un sujet
   * soit refusé car non réaliste, réalisable, déjà fait, trop cher...
 * l'administrateur aura un dashboard de toutes les décisions et propals.
 * l'administrateur validera les nouvelles catégories proposées
 * l'utilisateur aura son propre dashboard sur ses propal
 * L'utilisateur pourra avoir des propals favorite
 * l'utilisateur est informé de l'évolution et du status de sa propal

S'il reste du temps, on pourrait implémenter un mode "challenge" qui permet dans sur un thème déterminé et un temps donné de challengé les utilisateurs de la plate-forme.


## Qu'est-ce qu'il résout ?

La plate-forme doit permettre de rendre visible l'offre des idées et de recenser des propals partagées par le plus grand nombre

## La cible

Tout le monde a des irritants et une idée pour le résoudre: on peut partager cet irritant et trouver une solution.

## Mise en place technique

1. une BDD avec users, admins, propals, comments, likes, catégories
2. page d'inscription et de connexion
3. un espace pour les admin 
4. un espace perso pour les utilisateurs
5. un mailer pour les échanges et décisions asynchrones


# Et après ?
Proposer la plate-forme pour les entreprises qui souhaitent mettre en oeuvre un solution en mode Saas

# Définition
## l'idéation ?
C'est le fait de proposer des idées dans ta boîte pour améliorer :
- un process
- un espace au bureau
- la responsabilité sociétale des organisations
- le développement durable
- un outil nuémrique qui déchire et fait en 5 min ce que tu faisais en 3h !
- etc...

Sinon, tu peux suivre cette vidéo [ici](https://www.youtube.com/watch?v=IEc-QKZPQjU)