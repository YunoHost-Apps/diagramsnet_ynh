# Diagrams.net pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/diagramsnet.svg)](https://dash.yunohost.org/appci/app/diagramsnet) ![](https://ci-apps.yunohost.org/ci/badges/diagramsnet.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/diagramsnet.maintain.svg)  
[![Installer Diagrams.net avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=diagramsnet)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Diagrams.net rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

Application en ligne qui permet de faire des schémas et du dessin vectoriel

**Version incluse :** 18.0.6~ynh1

**Démo :** https://app.diagrams.net/

## Captures d'écran

![](./doc/screenshots/screenshot.png)

## Avertissements / informations importantes

## YunoHost specific features

* Integration of third-party websites (Dropbox, Google, Trello, etc.) is disabled.

## Documentations et ressources

* Site officiel de l'app : https://www.diagrams.net/
* Documentation officielle de l'admin : https://www.diagrams.net/doc
* Dépôt de code officiel de l'app : https://github.com/jgraph/drawio
* Documentation YunoHost pour cette app : https://yunohost.org/app_diagramsnet
* Signaler un bug : https://github.com/YunoHost-Apps/diagramsnet_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/diagramsnet_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/diagramsnet_ynh/tree/testing --debug
ou
sudo yunohost app upgrade diagramsnet -u https://github.com/YunoHost-Apps/diagramsnet_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps