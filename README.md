<!--
N.B.: This README was automatically generated by <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
It shall NOT be edited by hand.
-->

# FreeScout for YunoHost

[![Integration level](https://dash.yunohost.org/integration/freescout.svg)](https://ci-apps.yunohost.org/ci/apps/freescout/) ![Working status](https://ci-apps.yunohost.org/ci/badges/freescout.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/freescout.maintain.svg)

[![Install FreeScout with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=freescout)

*[Read this README in other languages.](./ALL_README.md)*

> *This package allows you to install FreeScout quickly and simply on a YunoHost server.*  
> *If you don't have YunoHost, please consult [the guide](https://yunohost.org/install) to learn how to install it.*

## Overview

FreeScout is the super lightweight and powerful free open source help desk and shared inbox built with PHP (Laravel framework). Now you can enjoy free Zendesk & Help Scout without giving up privacy or locking yourself into a service you don't control.

**Shipped version:** 1.8.146~ynh1

**Demo:** <https://demo.freescout.net/login>

## Screenshots

![Screenshot of FreeScout](./doc/screenshots/screenshot.png)

## :red_circle: Antifeatures

- **Not totally free upstream**: The packaged app is under an overall free license, but with clauses that may restrict its use.

## Documentation and resources

- Official app website: <https://freescout.net/>
- Official admin documentation: <https://github.com/freescout-helpdesk/freescout/wiki/Installation-Guide>
- Upstream app code repository: <https://github.com/freescout-helpdesk/freescout>
- YunoHost Store: <https://apps.yunohost.org/app/freescout>
- Report a bug: <https://github.com/YunoHost-Apps/freescout_ynh/issues>

## Developer info

Please send your pull request to the [`testing` branch](https://github.com/YunoHost-Apps/freescout_ynh/tree/testing).

To try the `testing` branch, please proceed like that:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
or
sudo yunohost app upgrade freescout -u https://github.com/YunoHost-Apps/freescout_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
