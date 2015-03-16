#AlbinoMouse pour Shaarli#
par alexis j - https://liens.effingo.be/

AlbinoMouse est un template pour Shaarli.

Démo (frontend) : https://liens.effingo.be

Dépôt GitHub : https://github.com/alexisju/albinomouse-template/

Téléchargement : https://github.com/alexisju/albinomouse-template/archive/master.zip


### Installation ###

Copiez le template dans le dossier tpl et configurez le fichier data/options.php pour charger le template.

Votre fichier data/options.php devrait ressembler à ceci:

<?php
$GLOBALS['config']['RAINTPL_TPL'] = 'tpl/albinomouse-template/';
?>

Vous trouverez plus d'information à ce sujet sur le [wiki du Shaarli communautaire] (https://github.com/shaarli/Shaarli/wiki#changing-template)

Important : Pour l'utiliser ce template, vous devez utiliser la [version communautaire de Shaarli (> 0.0.43)] (https://github.com/shaarli/Shaarli).


### Conseils d'utilisation ###

Afin que ce template s'adapte à vos besoins, il est conseillé d'apporter quelques modifications manuellement, après l'installation d'Albinomouse:
 - page.header.html : personnalisation des boutons de navigations. Ils sont destinés à renvoyer vers des url externes (vers votre blog, vers votre page de contact, etc). Utilisez [Glyphicon] (http://getbootstrap.com/components/#glyphicons) pour personaliser les icônes. 
 Remarque : certains de ces boutons sont masqués lorsque vous êtes connecté à Shaarli (classe CSS "cachemoi") pour laisser place à d'autres options utiles. 

###Licences###
  - AlbinoMouse est disponible sous [licence GPLv3] (inc/albinomouse-licence.txt)
  - Glyphicons Halflings (http://getbootstrap.com) : [MIT Licence] (inc/fonts/glyphicon-licence.txt)
  - OpenSans (http://opensans.com) : [Apache Licence version 2.0] (inc/fonts/opensans-license.txt)

###Crédit###
Le template AlbinoMouse pour Shaarli est directement inspiré du thème [AlbinoMouse pour WordPress](http://www.pixelstrol.ch/en/wp-themes/albinomouse/) développé par Stefan Brechbühl.
