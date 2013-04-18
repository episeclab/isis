Bienvenue sur IsisProject 2013
==============================

La mission
----------
Une société vous donne un site web développé par le fils du président de la boite, vous devez sécuriser son code tout en restant concis dans vos modifications.

Komenkonfaitlisis?
------------------
http://git.sec-l.org/

Je n'ai pas de mot-de-passe pour me connecter
---------------------------------------------
- Mettez votre adresse email login_x@epitech.eu ici: http://git.sec-l.org/users/password/new
- Cliquez sur le lien dans le mail
- Choisissez un nouveau mot-de-passe

Git ?
-----

- http://learn.github.com/
- http://try.github.com/

Comment `pull` le repo depuis le serveur git ?
----------------------------------------------
- Générez une clé ssh si vous n'en avez pas déjà une `man ssh-keygen`
- Ajoutez votre clé ssh sur http://git.sec-l.org/keys
- Vous trouverez l'adresse de votre repo dans la partie `home` du repo, l'url ressemble à `git@git.sec-l.org:isis2013/isis-XXXXXXXX.git`
- Dans un terminal: `git pull git@git.sec-l.org:isis2013/isis-XXXXXXX.git`

Installation avec apache2 sous linux
------------------------------------
TODO

Y aura-t'il une session d'attaque ?
-----------------------------------
Ça dépend de la participation des gens à l'Isis cette année et des projets dans votre emploi du temps

*Si* c'est le cas, nous ne mettrons que les repos ayant eu des bonnes modifications, et il n'y aura pas de malus pour les teams se faisant attaquer, mais seulement des bonus pour les teams qui réussissent à attaquer les autres.

Est-ce que je peux utiliser la lib X ou la lib Y ?
--------------------------------------------------
Non. On ne vous demande pas de recoder tout le site, simplement de patcher les failles.  
Vos changements doivent donc être les plus simples et courts possible.

Notation
--------
Vous serez corrigés sur la qualité de vos patches

Nous attribuons quelques bonus, voici des exemples de points que nous aimons bien voir :

+ :+1: utilisation du système d'issues
+ :+1: travail en équipe
+ :+1: bons messages de commits
+ :+1: commits séparés par fonctionnalités / groupe de modifications logique
+ :+1: avoir un git configuré et un [gravatar](http://gravatar.com/)
+ :+1: code intelligent, tricks sympas
+ :+1: écriture d'un changelog
+ :+1: si vous avez un compte github actif
+ :+1: contribution à ce repository, par exemple en ajoutant un script d'install du site sous apache2 pour aider les autres élèves

Et d'autres points que nous n'aimons pas et qui donnent des malus:

- :-1: commits en root
- :-1: gros commits pour petits changements
- :-1: commits inutiles 

Si vous pensez mériter des bonus, vous pouvez laisser un fichier bonus.txt à la racine du repos pour être sûr que nous ne passerons pas à coté

J'ai un problème et je ne trouve pas la réponse
-----------------------------------------------

Dans l'ordre:
- vérifiez qu'il n'y a pas la réponse dans cette faq ou dans les mails qu'on vous envoie
- regardez si il n'y a pas déjà une issue Github ([ouverte](https://github.com/episeclab/isis/issues?page=1&state=open) ou [fermée](https://github.com/episeclab/isis/issues?page=1&state=closed))
- demandez sur irc: ##esl (irc.freenode.net:6667) ou envoyez un email à isis@episeclab.org
