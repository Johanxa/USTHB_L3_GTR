# USTHB_L3_GTR
Ce répertoire est dédié à mon mémoire de fin de cycle licence génie des télécommunications et réseaux.

Le thème de mon projet était : __L'étude et le déploiement d'un pare-feu dans une entreprise.__
Afin d'expliquer au mieux les étapes de création de notre solution, j'ajouterai également les liens pour le téléchargement de toutes les ressources utilisées.

#Ressources : 
Lien de téléchargement du pare-feu OPNsense : https://opnsense.org/download/
Lien de téléchargement d'Odoo : https://bitnami.com/stack/odoo
Explication du module Zenarmor : https://www.sunnyvalley.io/sensei
Lien de téléchargement Ubuntu Budgie : https://ubuntubudgie.org/downloads/


##Plan
1. Chapitre 1 : Généralités sur la cybersécurité
2. Chapitre 2 : Notions théoriques sur les réseaux et la cybersécurité
3. Chapitre 3 : conception et implémentation de la solution.

Le but de notre projet était l’étude d’une solution basée sur un pare-feu afin de sécuriser le réseau d’une nouvelle direction régionale.  
Pour ce faire, nous avons évalué différentes solutions propriétaires et Open Source afin de réaliser un modèle d’implémentation réaliste et peu coûteux. N'ayant pas de ressource notre simulation s'est appuyée sur notre réseau local domestique. Voici une image qui englobe l'architecture générale :   
![image](https://user-images.githubusercontent.com/88862381/185247457-60d5fc7a-3476-47d5-8843-9b8f6581fa5a.png)


Pour la réalisation de notre solution de sécurité, nous avons choisi le pare-feu \\OPNsense. Ce choix est dû à de multiples facteurs, notamment :  
— L'outils choisi est Open Source, un certain niveau de liberté est ainsi permis en comparaison à certaines solutions certes sécurisées mais standardisées. Il est possible de créer ces propres scripts donc de répondre d’une manière plus centralisée et efficace aux besoins de l’entreprise.  
— Il est envisageable de modifier le code source comme l’entreprise le souhaite, et d’ajouter ou de supprimer des modules déjà existants. Dans le cas d’Algérie Télécom, certains services plus sophistiqués se devaient d’être présents tels que : la détection par intelligence artificielle d’un futur état de congestion. Ce travail nécessite un pare-feu qu’il est possible d’améliorer de manière libre.  
— L’un des atouts majeurs d'OPNsense est son prix. En effet, il est gratuit ce qui implique la possibilité d’avoir un pare-feu à la fois gratuit, centré sur les objectifs de sécurité de l’entreprise, mais aussi étudié et mis à jour par une communauté très active.  
— Trés connu pour son érgonomie, il permet une expérience utilisateur plus agréable et rend le travail beaucoup plus simple, qu'il s'agisse de son interface graphique sur ordinateur, ou sur mobile.  

Pour le reste je laisse le fichier en pièce jointe, bonne lecture ! 
N'hésitez pas à laisser vos remarques afin d'améliorer mon travail.
Merci pour l'attention porté à mon travail et celui de mon binôme.
