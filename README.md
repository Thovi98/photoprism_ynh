<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Photoprism for YunoHost

[![Integration level](https://dash.yunohost.org/integration/photoprism.svg)](https://dash.yunohost.org/appci/app/photoprism) ![Working status](https://ci-apps.yunohost.org/ci/badges/photoprism.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/photoprism.maintain.svg)  
[![Install Photoprism with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=photoprism)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Photoprism quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

PhotoPrism® is an AI-Powered Photos App for the Decentralized Web. It makes use of the latest technologies to tag and find pictures automatically without getting in your way. You can run it at home, on a private server, or in the cloud.

### Features

- Browse all your photos and videos without worrying about RAW conversion, duplicates or video formats
- Easily find specific pictures using powerful search filters
- Includes four high-resolution world maps to bring back the memories of your favorite trips
- Play Live Photos™ by hovering over them in albums and search results
- Recognizes the faces of your family and friends
- Automatic classification of pictures based on their content and location


**Shipped version:** 2022.07.30~ynh3


**Demo:** https://demo-fr.photoprism.app

## Screenshots

![Screenshot of Photoprism](./doc/screenshots/photoprism.jpg)

## Disclaimers / important information

* Known limitations:
    * Although reaching level 7, Photoprism hasn't yet been extensively tested in real conditions
    * Please use with **extreme care** if you install it on a test server !
    * Not tested yet with AMD architecture
    * Photoprism currently supports only one user. OIDC should be supported within a few months
    * Photoprism requires an important amount of RAM and disk to install or to work properly

* All data is stored in `/home/yunohost.app/photoprism/photos/`
    * Be careful, this data is not backed-up by default when doing a backup

* At first install, you'll be prompted for credentials
    * Username is "admin"
    * Password is the password you have set during the installation

## Documentation and resources

* Official app website: <https://photoprism.app>
* Official user documentation: <https://docs.photoprism.app/user-guide/>
* Official admin documentation: <https://docs.photoprism.app/developer-guide/>
* Upstream app code repository: <https://github.com/photoprism/photoprism>
* YunoHost documentation for this app: <https://yunohost.org/app_photoprism>
* Report a bug: <https://github.com/YunoHost-Apps/photoprism_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/photoprism_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/photoprism_ynh/tree/testing --debug
or
sudo yunohost app upgrade photoprism -u https://github.com/YunoHost-Apps/photoprism_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
