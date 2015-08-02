#AlbinoMouse pour Shaarli#

AlbinoMouse est un template pour le [fork communautaire de Shaarli](https://github.com/shaarli/Shaarli) développé par [alexis j](https://liens.effingo.be).

Démo (frontend) : https://liens.effingo.be

Dépôt GitHub : https://github.com/alexisju/albinomouse-template/

Téléchargement : https://github.com/alexisju/albinomouse-template/archive/master.zip


### Installation ###
Dans votre répertoire tpl/, téléchargez et décompressez l'[archive zip du template](https://github.com/alexisju/albinomouse-template/archive/master.zip) ou lancez la commande `git clone https://github.com/alexisju/albinomouse-template.git`

Un sous-répertoire nommé albinomouse-template, contenant tous les fichiers du template, doit se trouver dans le répertoire tpl/

Modifiez ensuite le fichier de configuration `data/config.php` pour indiquer à Shaarli d'utiliser ce template :
```
$GLOBALS['config']['RAINTPL_TPL'] = 'tpl/albinomouse-template/';
```

Vous trouverez plus d'information à ce sujet sur le [wiki du Shaarli communautaire] (https://github.com/shaarli/Shaarli/wiki/Theming)

**Important** : Pour utiliser ce template, vous devez utiliser la **[dernière version communautaire de Shaarli](https://github.com/shaarli/Shaarli)**.

### Conseils d'utilisation ###

Afin que ce template s'adapte à vos besoins, je vous conseille de modifier le fichier `page.header.html` après son installation. Vous pourrez ainsi personnaliser les boutons de navigations. Ils sont destinés à renvoyer vers des url externes (vers votre blog, vers votre page de contact, etc). 

Vous pouvez personnaliser les icônes du menu facilement grâce à [Glyphicon](http://getbootstrap.com/components/#glyphicons).

Remarque : certains éléments du menus sont volontairement masqués lorsque vous êtes connecté à Shaarli (classe CSS "cachemoi") pour laisser place à d'autres options utiles. 

###Licences###
  - AlbinoMouse est disponible sous [licence GPLv3] (inc/albinomouse-licence.txt)
  - Glyphicons Halflings (http://getbootstrap.com) : [MIT Licence] (inc/fonts/glyphicon-licence.txt)
  - OpenSans (http://opensans.com) : [Apache Licence version 2.0] (inc/fonts/opensans-license.txt)

###Crédit###
Le template AlbinoMouse pour Shaarli est directement inspiré du thème [AlbinoMouse pour WordPress](http://www.pixelstrol.ch/en/wp-themes/albinomouse/) développé par Stefan Brechbühl.
