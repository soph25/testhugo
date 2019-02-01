+++
date = "2019-01-30"
publishdate = "2019-01-30T01:13:16+01:00"
type = "post"
title = "installer-Hugo-2"
slug = "installer-Hugo-2"
tags = ["posts", "interesting"]
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
**Deuxieme étape indispensable :**   
Retourner dans le dossier de votre site sur votre machine, et créez un fichier  "netlify.toml" à la racine de votre site près du fichier "config.toml".

le contenu a inclure dans le fichier permettra a  Netlify de monter votre signe en ligne. Le contenu a inclure est disponible sur le site de Hugo 

si tout fonctionne correctement votre site est maintenant en ligne avec une url de type 
https://********.netlify.com/
la partie étoilée peut etre changee si elle ne vous convient pas
sinon vous pouvez aussi rediriger vos contenus sur un site deja existant https://.... c est une option qui est proposée 
