# Drupal 7 pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/drupal7.svg)](https://dash.yunohost.org/appci/app/drupal7)  
[![Install Drupal 7 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=drupal7)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Drupal 7 rapidement et simplement sur un serveur Yunohost.  
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble
Framework de gestion de contenu libre et open-source.

**Version incluse:** 7

## Captures d'écran

![](https://www.drupal.org/files/issues/D7-screenshot.png)

## Configuration

Comment configurer cette application: via le panneau d'administration, un fichier brut en SSH ou tout autre moyen.

## Documentation

 * Documentation officielle: https://www.drupal.org/docs/7

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateurs

L'authentification LDAP et HTTP est-elle prise en charge?
L'application peut-elle être utilisée par plusieurs utilisateurs?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/drupal7%20%28Community%29.svg)](https://ci-apps.yunohost.org/ci/apps/drupal7/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/drupal7%20%28Community%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/drupal7/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/drupal7%20%28Community%29.svg)](https://ci-stretch.nohost.me/ci/apps/drupal7/)

## Limitations

* Limitations connues.

## Informations additionnelles

* Autres informations à ajouter sur cette application

**Plus d'informations sur la page de documentation:**  
https://yunohost.org/packaging_apps

## Links

 * Signaler un bug: https://github.com/YunoHost-Apps/drupal7_ynh/issues
 * Site de l'application: https://www.drupal.org
 * Site web YunoHost: https://yunohost.org/

---

Informations pour les développeurs
----------------

**Seulement si vous voulez utiliser une branche de test pour le codage, au lieu de fusionner directement dans la banche principale.**
Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing --debug
ou
sudo yunohost app upgrade drupal7 -u https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing --debug
```
