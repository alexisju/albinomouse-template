#AlbinoMouse pour Shaarli#

AlbinoMouse est un template pour le [fork communautaire de Shaarli](https://github.com/shaarli/Shaarli) développé par [alexis j](https://liens.effingo.be).

Démo (frontend) : https://liens.effingo.be

Dépôt GitHub : https://github.com/alexisju/albinomouse-template/


### Installation ###
Dans votre répertoire tpl/, téléchargez et décompressez l'[archive zip du template](https://github.com/alexisju/albinomouse-template/archive/master.zip) ou lancez la commande `git clone https://github.com/alexisju/albinomouse-template.git`

Un sous-répertoire nommé albinomouse-template, contenant tous les fichiers du template, doit se trouver dans le répertoire tpl/

Modifiez ensuite le fichier de configuration `data/config.php` pour indiquer à Shaarli d'utiliser ce template :
```
$GLOBALS['config']['RAINTPL_TPL'] = 'tpl/albinomouse-template/';
```

Vous trouverez plus d'information à ce sujet sur le [wiki du Shaarli communautaire] (https://github.com/shaarli/Shaarli/wiki/Theming)

**Important** : Ce template est destiné à être utilisé avec la **[dernière version stable du fork communautaire de Shaarli](https://github.com/shaarli/Shaarli/releases)**.

### Conseils d'utilisation ###

Depuis la version 0.6.0, le [système de plugin](https://github.com/shaarli/Shaarli/wiki/Plugin-System) est maintenant opérationel et intégré à ce template. 
Depuis la version 0.6.3, le [gestionnaire de plugin](https://github.com/shaarli/Shaarli/wiki/Plugin-installation-%26-configuration) est également supporté.

En complément avec ce template, je vous conseille d'utiliser les plugins ci-dessous que j'ai développé pour s'intégrer à AlbinoMouse :
 - [Menu](https://github.com/alexisju/menu) : créer un menu personnalisé qui vous permettra de faire la mise à jour du template plus facilement ;
 - [Social](https://github.com/alexisju/social) : un outil discret de repartage de vos liens vers les réseaux sociaux ;
 - [Qrcode](https://github.com/alexisju/qrcode_albinomouse) : un plugin alternatif au plugin par défaut pour afficher vos liens sous forme de QR-Codes.
 - [Go to top](https://github.com/alexisju/gototop) : ajoute un lien, en pied de page, pour remonter en haut de la page.

Les icônes du menu sont personnalisables grâce à [Glyphicon](http://getbootstrap.com/components/#glyphicons) intégré au template.

Remarque : certains éléments du menus peuvent être masqués automatiquement lorsque vous êtes connecté à Shaarli en ajoutant la classe CSS "cachemoi"

###Licences###
  - AlbinoMouse est disponible sous [licence GPLv3] (inc/albinomouse-licence.txt)
  - Glyphicons Halflings (http://getbootstrap.com) : [MIT Licence] (inc/fonts/glyphicon-licence.txt)
  - OpenSans (http://opensans.com) : [Apache Licence version 2.0] (inc/fonts/opensans-license.txt)

###Crédit###
Le template AlbinoMouse pour Shaarli est directement inspiré du thème [AlbinoMouse pour WordPress](http://www.pixelstrol.ch/en/wp-themes/albinomouse/) développé par Stefan Brechbühl.
