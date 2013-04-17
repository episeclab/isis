Au secours, mon site est tout cassé !
=====================================

Des lignes de PHP s'affiche en plein milieu de ma page
------------------------------------------------------
Cela vient d'une mauvaise configuration de PHP.
Afin de régler le soucis, il faut activer les short tags dans la conf PHP.
Pour ce faire, éditez le fichier php.ini (/etc/php5/apache2/php.ini par défaut sur debian) et rajoutez la ligne suivante au début du fichier, après [PHP]:
```
short_open_tag = On
```

Mon prestashooph part en boucle infinie !
-----------------------------------------
Modifiez le fichier www/templates/home.tpl, et remplacez la ligne :
```php
 for ($i = 0; $products[$i] !== false; ++$i):
```
par :
```php
 for ($i = 0; $i < count($products); ++$i):
```
