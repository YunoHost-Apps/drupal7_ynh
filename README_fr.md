# Drupal 7 pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/drupal7.svg)](https://dash.yunohost.org/appci/app/drupal7) ![](https://ci-apps.yunohost.org/ci/badges/drupal7.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/drupal7.maintain.svg)  
[![Installer drupal7 avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=drupal7)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer drupal7 rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
Framework de gestion de contenu libre et open-source.

**Version incluse:** 7.84

## Captures d'écran

![](https://www.drupal.org/files/issues/D7-screenshot.png)

## Documentation

 * Documentation officielle: https://www.drupal.org/docs/7

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

Le module d'authentification LDAP peut être installé

#### Architectures supportées

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/drupal7.svg)](https://ci-apps.yunohost.org/ci/apps/drupal7/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/drupal7.svg)](https://ci-apps-arm.yunohost.org/ci/apps/drupal7/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/drupal7_ynh/issues
 * Site de l'application : https://www.drupal.org
 * Site web YunoHost: https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing --debug
ou
sudo yunohost app upgrade drupal7 -u https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing --debug
```
