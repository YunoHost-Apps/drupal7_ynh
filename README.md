# Drupal 7 for YunoHost

[![Integration level](https://dash.yunohost.org/integration/drupal7.svg)](https://dash.yunohost.org/appci/app/drupal7)  
[![Install Drupal 7 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=drupal7)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Drupal 7 quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Free and open-source content management framework.

**Shipped version:** 7.67

## Screenshots

![](https://www.drupal.org/files/issues/D7-screenshot.png)

## Documentation

 * Official documentation: https://www.drupal.org/docs/7

## YunoHost specific features

#### Multi-users support

LDAP module can be installed

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/drupal7%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/drupal7/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/drupal7%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/drupal7/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/ci/logs/drupal7%20%28Apps%29.svg)](https://ci-stretch.nohost.me/ci/apps/drupal7/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/drupal7_ynh/issues
 * App website: https://www.drupal.org
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing --debug
or
sudo yunohost app upgrade drupal7 -u https://github.com/YunoHost-Apps/drupal7_ynh/tree/testing --debug
```
