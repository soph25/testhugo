+++
date = "2019-02-01"
publishdate = "2019-02-01T21:03:54+01:00"
type = "post"
title = "cenom-lahaut-pla"
slug = "cenom-lahaut-pla"
tags = ["posts", "interesting"]
categories = ["uncategorized"]
image = "/images/test.jpg"
+++

# D'abord installer Hugo
sur linux j ai fait sudo apt-get install hugo mais il vaut mieux recuperer la derniere version sur leur depot https://github.com/gohugoio/hugo/releases

** ATTENTION **

**il semble préférable de disposer de la dernière version qui la 0.53 sinon cela peut poser des problèmes pour produire le contenu car certaines fonctions ne seront pas reconnues.****

# quand l installation est faite

en ligne de commande : hugo new site "lenomdevotresite"

cela genere les fichiers pour produire le contenu. Mais attention **il faut charger un thème ** depuis leur librairie le site https://gohugo.io/  en montre des exemples sur un onglet thèmes
il faut installer le thème dans un dossier themes avec les autres dossiers. Si vous disposez de la bonne version d Hugo le theme choisit s installe sans difficulté, sinon recommencez ...

# quand vous etes satisfait de vos contenus

vous pouvez mettre en ligne votre site, **en utilisant d abord github ou gitlab** et poussez vos contenus sur un nouveau repository. Ensuite très facilement , j insiste, utilisez Netlify, il faut se créer un compte gratuit . C est plus pratique de s inscrire diretement en utilisant son accès github car Netlify va utiliser github pour installer votre site. Les autorisations nécessaires ne seront plus a remplir.