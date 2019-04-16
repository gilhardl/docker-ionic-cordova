# docker-ionic-cordova

Docker image for Ionic Cordova development, based on [gilhardl/ionic](https://github.com/gilhardl/docker-ionic)

[![Docker Pulls](https://img.shields.io/docker/pulls/gilhardl/ionic-cordova.svg?style=flat-square&label=PULLS)](https://hub.docker.com/r/gilhardl/ionic-cordova/)

---

![OS](https://img.shields.io/static/v1.svg?style=flat-square&label=OS&message=Linux%20Alpine)

![OPEN JDK](https://img.shields.io/static/v1.svg?style=flat-square&label=OPEN%20JDK&message=8u191&color=informational)

![ANDROID SDK](https://img.shields.io/static/v1.svg?style=flat-square&label=ANDROID%20SDK&message=25.2.5&color=informational)
![ANDROID BUILD TOOLS](https://img.shields.io/static/v1.svg?style=flat-square&label=ANDROID%20BUILD%20TOOLS&message=27.0.0&color=informational)

![IONIC CLI](https://img.shields.io/npm/v/ionic.svg?style=flat-square&label=IONIC%20CLI)
![ANGULAR CLI](https://img.shields.io/npm/v/@angular/cli.svg?style=flat-square&label=ANGULAR%20CLI)

![NODE](https://img.shields.io/npm/v/node/lts.svg?style=flat-square&label=NODE)
![NPM](https://img.shields.io/npm/v/npm/lts.svg?style=flat-square&label=NPM)
![YARN](https://img.shields.io/npm/v/yarn/latest.svg?style=flat-square&label=YARN)

![PACKAGE MANAGER](https://img.shields.io/static/v1.svg?style=flat-square&label=PACKAGE%20MANAGER&message=Yarn)

---

# Usage

```
docker run -it --name ionic-cordova -v /path/to/your/project:/usr/src/app gilhardl/cordova-ionic
```

# Licence

MIT