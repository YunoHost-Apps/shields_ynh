<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Shields YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/shields)](https://ci-apps.yunohost.org/ci/apps/shields/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/shields)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/shields)

[![Instalatu Shields YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=shields)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Shields YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Shields.io is a service for concise, consistent, and legible badges in SVG and raster format, which can easily be included in GitHub readmes or any other web page. The service supports dozens of continuous integration services, package registries, distributions, app stores, social networks, code coverage services, and code analysis services.

**Paketatutako bertsioa:** 2025.02.02~ynh1

## Pantaila-argazkiak

![Shields(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://shields.io/>
- Administratzaileen dokumentazio ofiziala: <https://shields.io/docs>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/badges/shields>
- YunoHost Denda: <https://apps.yunohost.org/app/shields>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/shields_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/shields_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/shields_ynh/tree/testing --debug
edo
sudo yunohost app upgrade shields -u https://github.com/YunoHost-Apps/shields_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
