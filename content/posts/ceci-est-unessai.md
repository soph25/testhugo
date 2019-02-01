+++
date = "2019-01-30"
publishdate = "2019-02-01T20:45:22+01:00"
type = "post"
title = "ceci-est-unessai"
slug = "ceci-est-unessai"
tags = ["posts", "interesting"]
categories = ["uncategorized"]
image = "/images/test.jpg"
+++

# Bon vous avez sans doute écrit quelques articles de test
# Bon vous avez sans doute écrit quelques articles de test
# Bon vous avez sans doute écrit quelques articles de test
Alors vous avez constaté qu il n est pas facile ni agréable d écrire dans les fichiers md. C est pourquoi j ai recherché un outil d édition qui puisse aider dans ce sens.

En fait il y a plusieurs problémes , le premier est celui lié a la rédaction que je viens d évoquer et un second qui est plus ardu et plus embétant aussi.

En effet on se rend vite compte que même si Netlify fonctionne bien , il faut pour mettre a jour pousser a chaque fois les fichiers dans git et les envoyer dans le repository. Cela a beau être facile à faire cela me parait difficile à maintenir. Il existe des **webhooks ** qui peuvent faire ce travail et sont proposés dans le service de Netlify. Mais bon il faut les mettre en place et cela n'a pas l air évident.

Troisiéme problème, il n y a aucune possibilté pour des utilisateurs de modifier le contenu des pages statiques que nous mettons en ligne.

# J'ai donc cherché un outil qui puisse aider dans les 3 situations

Bien sur j ai cherché un outil opensource de préférence et j ai trouvé Cockpit https://getcockpit.com/

Pour l instant j ai réussi a le mettre en place pour résoudre le probléme d édition mais cet outil propose la gestion des webhooks a voir donc... Pour le dernier probléme je ne pense pas qu il existe de solution facile . Il existe des services comme Forestry.io qui propose en package la création d un site jekyll , la mise en ligne et un dashboard d administration pour écrire et mettre a jour les contenus... il en existe d 'autres aussi vous pouvezvoir cela sur https://gohugo.io/tools/frontends/

Bon finalement je vous parlerais de la mise en place de Cockpit et de l editeur dans mon troisieme post

