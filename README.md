# ClubMed 🌞⛱🌊

À partir de données réelles du Club Med, l'objectif est d'abord de réussir à prédire :

<i>Qui sont les clients plus susceptibles de revenir l'année suivante ?</i>

Ensuite, l'objectif est d'effectuer une recommandation cohérente avec le profil du client.

Nous utilisons pour cela le langage de programmation SAS et nous construisons une grille de score à partir des scores obtenus via une régression logistique.

Le système de recommandation est construit "manuellement", je me suis basé sur l'historique de chaque voyageur et j'ai identifié les différents parcours les plus souvent effectués. 
Ainsi, lorsqu'un client semble être dans un <i>pattern</i> connu, nous lui recommandons la destination suivante. Dans le cas contraire, nous recommandons la destination la plus souvent sélectionnée par les autres voyageurs en fonction de sa dernière destination.

Support de présentation du projet : 
https://www.canva.com/design/DAE7uXn78Dg/SpFtoKVVicNFhCNLkJ-RWQ/view?utm_content=DAE7uXn78Dg&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink
