#AlbinoMouse pour Shaarli#

AlbinoMouse est un template pour [ Shaarli](https://github.com/shaarli/Shaarli) développé par [alexis j](http://liens.effingo.be).

Live demo (frontend) : http://liens.effingo.be

Dépôt GitHub : https://github.com/alexisju/albinomouse-template/

Capture d'écran du template avec les plugins [am_menu](https://github.com/alexisju/am_menu) et [social](https://github.com/alexisju/social)  activés :

![screenshot](https://raw.githubusercontent.com/alexisju/albinomouse-template/master/inc/screenshot.png)


### Installation ###

Dans votre répertoire tpl/, téléchargez et décompressez l'[archive zip du template](https://github.com/alexisju/albinomouse-template/archive/master.zip) ou lancez la commande `git clone https://github.com/alexisju/albinomouse-template.git`

Un sous-répertoire nommé albinomouse-template, contenant tous les fichiers du template, doit se trouver dans le répertoire tpl/

Dans votre instance de Shaarli, modifiez ensuite le fichier de configuration `data/config.json.php` et modifiez le paramètre `raintpl_tpl` en `tpl\/albinomouse-template/`pour indiquer à Shaarli d'utiliser ce template :


```json
{
    "resource": {
        "raintpl_tpl": "tpl\/albinomouse-template/",
        [...]
    }
}
```

A partir de la version de 0.8.2 de Shaarli, après avoir téléchargé le template dans le répertoire adhoc, vous pouvez activer le template directement depuis l'interface de configuration de Shaarli.

Vous trouverez plus d'information à ce sujet sur le [wiki du Shaarli communautaire] (https://github.com/shaarli/Shaarli/wiki/Theming)

**Important** : Ce template est destiné à être utilisé avec la **[dernière version stable du fork communautaire de Shaarli](https://github.com/shaarli/Shaarli/releases)**.

### Plugins ###

En complément avec ce template, je vous conseille d'utiliser les plugins ci-dessous que j'ai développé pour s'intégrer à AlbinoMouse :
 - [AM_Menu](https://github.com/alexisju/am_menu) : ajoute un menu personalisable au template. Il vous permettra de faire la mise à jour du template plus facilement car vous ne devrez plus modifier le template lui-même pour l'adapter à vos besoins ;
 - [Social](https://github.com/alexisju/social) : un outil discret de repartage de vos liens vers les réseaux sociaux ;
 - [Qrcode](https://github.com/alexisju/am_qrcode) : un plugin alternatif au plugin par défaut pour afficher vos liens sous forme de QR-Codes.
 - [Go to top](https://github.com/alexisju/gototop) : ajoute un lien, en pied de page, pour remonter en haut de la page.

Les icônes du menu sont personnalisables grâce à [Glyphicon](http://getbootstrap.com/components/#glyphicons) intégré au template.

###Licences###

  - AlbinoMouse est disponible sous [licence GPLv3] (inc/albinomouse-licence.txt)
  - Glyphicons Halflings (http://getbootstrap.com) : [MIT Licence] (inc/fonts/glyphicon-licence.txt)
  - OpenSans (http://opensans.com) : [Apache Licence version 2.0] (inc/fonts/opensans-license.txt)

###Crédit###
Le template AlbinoMouse pour Shaarli est directement inspiré du thème [AlbinoMouse pour WordPress](https://wpzoo.ch/en/themes/albinomouse/) développé par Stefan Brechbühl.
