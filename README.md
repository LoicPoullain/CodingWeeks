# Groupe 15 - Développement d'applications web en Django

==================================================================

**Pense-bêtes de Loïc pour l'année prochaine**

_Choses à faire avant de mettre en ligne le tutoriel :_
- _créer et mettre en lien l'excel listant les binômes,_
- _créer les canaux 1A et 3A et ajouter le lien d'invitation de Slack,_
- _ajouter le lien vers le test EDUNAO sur Git (fichier git-and-gitlab.md)._

_Choses pouvant être améliorées dans le tutoriel les années suivantes :_
- _Dans S1_F1, enlever toute la mention sur les autres BDD avec le `settings.py`. Les élèves sont perdus avec. On pourra la déplacer dans la section "Aller plus loin" et créer "utiliser une autre base de données" par exemple._
- _Enlever les `re_path` avec les regex. C'est pas très compréhensible pour les élèves et pas forcément utile. Passer à la notation `path('<int:product_id>')` à la place._

_Idées de petits cours à donner la première semaine :_
- _Git et Gitlab_.
- _Requêtes HTTP. Exemples avec des formulaires et des fichiers statiques._
- _Introduction à la programmation objet._
- _Comprendre ce qu'est un type._

_Lien de la boîte à outils : https://github.com/LoicPoullain/je-code_

==================================================================

Bienvenue aux Coding Weeks !

Ce séminaire de deux semaines va vous permettre de monter en compétences en développement et développement web (utilisation de Git, Gitlab, python, Django, etc). A l'issue de cette période, vous serez en mesure de créer un petit site web fonctionnel.

Ce cours sera divisé en deux séquences. La première semaine sera dédiée à l'apprentissage. La seconde sera une semaine projet où vous développerez une application web de votre choix sur laquelle vous serez notée.

C'est parti !

## Prérequis

Avant de commencer, merci de bien vouloir :
- vous mettre par équipe de deux et de noter votre binôme sur cet [excel](#),
- et rejoindre les canaux #cw15_webapp et #cw_important_information
 sur [Slack](#).

> Slack est une plateforme de communication collaborative très utilisée en entreprise. C'est par ce biais que vous pourrez discuter entre vous, partager du code et recevoir des informations complémentaires de la part des encadrants. Vous pouvez soit télécharger l'application Slack ou utiliser la version en ligne.

### Visual Studio Code (VSCode)

Pour ces deux semaines, nous vous recommandons fortement d'installer et d'utiliser [Visual Studio Code](https://code.visualstudio.com/) (à ne pas confondre avec Visual Studio) qui est un éditeur qui s'est beaucoup popularisé ces dernières années. Il est très adapté à python et au développement web et, surtout, il est très facile à prendre en main et à comprendre. Les démonstrations au tableau seront faites avec celui-ci.

Vous pouvez utiliser un autre éditeur si vous le souhaitez. Ce sera alors de votre responsabilité de savoir l'utiliser.

:point_right: _[Je ne sais pas utiliser VSCode](https://github.com/LoicPoullain/je-code/blob/master/utiliser-visual-studio-code.md)._

## Semaine 1

Durant cette semaine, des micro-cours seront donnés chaque matin de 9h à 9h30. Le reste du travail se fera en autonomie via les tutoriels ci-dessous (à faire dans l'ordre).

> _Vous pouvez bien évidemment susciter l'aide de l'encadrant si vous êtes bloqué mais n'hésitez pas, dans un premier un temps, à lire les messages d'erreur s'il y en a et à essayer de les résoudre._

### Création d'un dépôt Gitlab

[Suivre le tutoriel Gitlab](./semaine-1/git-and-gitlab.md).

### Configurer l'environnement de développement 

[Suivre le tutoriel sur la configuration de votre environnement de développement](./semaine-1/virtual-environment.md).

### Dévelopment d'une application Web en Django

[Suivre le tutoriel Django](./semaine-1/python-django.md).

<!--
## Semaine 2

**Consignes pour la soutenance**

**Dépôt Gitlab**
- @Loïc Poullain et @celine.hudelot doivent être ajoutés au dépôt en reporter .
- Seule la branche master sera corrigée. Assurez-vous de mettre votre dernière version stable dessus.
- Votre README doit contenir au début la liste des membres et la description du projet.
- Créez un fichier requirements.txt avec la commande pip freeze > requirements.txt pour lister vos dépendances.
- Deadline : cette nuit. Vendredi à 6h, je dois avoir votre dernière version du code sur master.

**Présentation**
- Produisez un seul document Powerpoint pour la présentation. Commitez-le sur votre dépôt et n'oubliez d'en exporter une version PDF. Il doit être commité sur votre dépôt avant la soutenance.
- 15 minutes de présentation (avec une démonstration en direct du produit)
- 5 minutes de questions
- 5 minutes de débrief
- IMPORTANT : soyez ponctuels. Connectez-vous sur le MSTeams de groupe Applications Web 2 à 3 minutes avant votre heure de passage. Votre présentation et votre démo doivent être prêtes. Vous les avez sur un ordinateur de rechange au cas où.

**Notation (à titre indicatif)**
- 1/3 de la note sur la présentation (merci de mettre vos caméras lors de la soutenance), le produit en lui-même et votre gestion de projet et travail en équipe.
- 2/3 de la note sur l'aspect technique
-->
