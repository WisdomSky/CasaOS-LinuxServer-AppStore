
![CasaOS LinuxServer AppStore](https://raw.githubusercontent.com/WisdomSky/CasaOS-LinuxServer-AppStore/main/banner.png)

# CasaOS LinuxServer AppStore

A CasaOS custom Appstore containing over 100+ [LinuxServer.io](https://www.linuxserver.io/) images.




## 📃 Table of Contents

- [Introduction](#-introduction)
- [Installation](#-installation)
- [List of Applications](#-list-of-applications)
- [Frequently Asked Questions / FAQs](#-frequently-asked-questions)
    - [How to Upgrade CasaOS](#-how-to-upgrade-casaos)
    - ["Error 404: Not Found" during install](#-error-404-not-found-during-install)
    - [How to uninstall the LinuxServer Appstore](#-how-to-uninstall-the-linuxserver-appstore)
- [Contributing](#contributing)

---

## 🔥 Introduction

The **LinuxServer AppStore** is a custom appstore built to work for [CasaOS](https://github.com/IceWhaleTech/CasaOS).

This custom appstore for CasaOS contains a wide variety of configurations of docker images built and maintained by the [linuxserver.io](https://www.linuxserver.io/) community which are adapted to work for CasaOS.

The LinuxServer Appstore is **guaranteed to provide you the latest version of every Application** as the appstore automatically tracks new releases and updates the contents of this repository daily.


---


## ✅ Installation

Run the following command to install the appstore:
```bash
casaos-cli app-management register app-store https://casaos-appstore.paodayag.dev/linuxserver.zip
```

> **NOTE: Custom Appstore is only supported on CasaOS version [0.4.4](https://blog.casaos.io/blog/23.html) and above. How to upgrade? [Click here](#-how-to-upgrade-casaos)**

---

## 🛠 List of Applications

| Application  | Version | Project Page |
| --- | --- | --- |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/adguardhomesync-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Adguardhome-sync](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Adguardhome-sync) | 0.4.14 | https://github.com/bakito/adguardhome-sync/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/airsonic-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Airsonic-advanced](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Airsonic-advanced) | 11.0.0 | https://airsonic.github.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/apprise-api.png" width="15"/>&nbsp;&nbsp;&nbsp;[Apprise-api](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Apprise-api) | 0.9.2 | https://github.com/caronc/apprise-api |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/audacity-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Audacity](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Audacity) | 3.3.3 | https://www.audacityteam.org/ |
| <img src="https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/babybuddy-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Babybuddy](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Babybuddy) | 1.16.0 | https://hub.docker.com/r/linuxserver/babybuddy |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/bazarr.png" width="15"/>&nbsp;&nbsp;&nbsp;[Bazarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Bazarr) | 1.2.2 | https://www.bazarr.media/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/beets-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Beets](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Beets) | 1.6.0 | http://beets.radbox.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/blender-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Blender](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Blender) | 3.6.0 | https://hub.docker.com/r/linuxserver/blender |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/boinc-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Boinc](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Boinc) | 7.20.5 | https://boinc.berkeley.edu/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/booksonic-air.png" width="15"/>&nbsp;&nbsp;&nbsp;[Booksonic-air](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Booksonic-air) | 2201.1.0 | https://booksonic.org/ |
| <img src="https://camo.githubusercontent.com/bc396d418b9da24e78f541bf221d8cc64b47c033/68747470733a2f2f73332d75732d776573742d322e616d617a6f6e6177732e636f6d2f6c696e75787365727665722d646f63732f696d616765732f626f6f6b737461636b2d6c6f676f353030783530302e706e67" width="15"/>&nbsp;&nbsp;&nbsp;[Bookstack](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Bookstack) | 23.05.2 | https://www.bookstackapp.com/ |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Budge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Budge) | 0.0.9 | https://hub.docker.com/r/linuxserver/budge |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Build-agent](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Build-agent) | version-cb7b1264 | https://hub.docker.com/r/linuxserver/build-agent |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/calibre-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Calibre](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Calibre) | 6.21.0 | https://calibre-ebook.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/calibre-web-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Calibre-web](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Calibre-web) | 0.6.20 | https://github.com/janeczku/calibre-web |
| <img src="https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/changedetection-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Changedetection.io](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Changedetection.io) | 0.43.1 | https://hub.docker.com/r/linuxserver/changedetection.io |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/chromium-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Chromium](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Chromium) | version-d77b49f2 | https://hub.docker.com/r/linuxserver/chromium |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Ci](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ci) | version-fff183d3 | https://hub.docker.com/r/linuxserver/ci |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/code-server.png" width="15"/>&nbsp;&nbsp;&nbsp;[Code-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Code-server) | 4.14.1 | https://github.com/cdr/code-server |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/cops-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Cops](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Cops) | 1.1.3 | https://github.com/seblucas/cops |
| <img src="https://raw.githubusercontent.com/linuxserver/beta-templates/master/lsiodev/img/daapd-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Daapd](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Daapd) | 28.6.20230621 | https://ejurgensen.github.io/forked-daapd/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/darktable-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Darktable](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Darktable) | 4.0.1 | https://www.darktable.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/davos.png" width="15"/>&nbsp;&nbsp;&nbsp;[Davos](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Davos) | 2.2.2 | https://github.com/linuxserver/davos |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/ddclient-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Ddclient](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ddclient) | 3.10.0 | https://github.com/ddclient/ddclient |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/deluge-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Deluge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Deluge) | 2.1.1 | http://deluge-torrent.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/digikam.png" width="15"/>&nbsp;&nbsp;&nbsp;[Digikam](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Digikam) | version-2023-04-21 | https://www.digikam.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/dillinger.png" width="15"/>&nbsp;&nbsp;&nbsp;[Dillinger](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Dillinger) | 3.39.1 | https://dillinger.io/ |
| <img src="https://raw.githubusercontent.com/shirosaidev/diskover/master/docs/diskover.png" width="15"/>&nbsp;&nbsp;&nbsp;[Diskover](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Diskover) | 2.1.0 | https://github.com/shirosaidev/diskover |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/dokuwiki-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Dokuwiki](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Dokuwiki) | version-2023-04-04a | https://www.dokuwiki.org/dokuwiki |
| <img src="https://github.com/domoticz/domoticz/raw/master/www/images/logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Domoticz](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Domoticz) | 2023.1.20230615 | https://www.domoticz.com |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/doplarr-logo_title.png" width="15"/>&nbsp;&nbsp;&nbsp;[Doplarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Doplarr) | 3.6.2 | https://hub.docker.com/r/linuxserver/doplarr |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/doublecommander-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Doublecommander](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Doublecommander) | version-4dd3c93a | https://doublecmd.sourceforge.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/duckdns.png" width="15"/>&nbsp;&nbsp;&nbsp;[Duckdns](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Duckdns) | version-45e56094 | https://www.duckdns.org/ |
| <img src="https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/duplicati-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Duplicati](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Duplicati) | 2.0.7 | https://www.duplicati.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/emby-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Emby](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Emby) | 4.7.13 | https://emby.media/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/embystat-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Embystat](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Embystat) | 0.2.0 | https://github.com/mregni/EmbyStat |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/emulatorjs-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Emulatorjs](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Emulatorjs) | 1.7.2 | https://hub.docker.com/r/linuxserver/emulatorjs |
| <img src="https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/openssh-server-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Endlessh](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Endlessh) | version-dfe44eb2 | https://github.com/skeeto/endlessh |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/fail2ban-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Fail2ban](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Fail2ban) | 1.0.2 | https://hub.docker.com/r/linuxserver/fail2ban |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/feed2toot-banner.png" width="15"/>&nbsp;&nbsp;&nbsp;[Feed2toot](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Feed2toot) | 0.17.20230624 | https://hub.docker.com/r/linuxserver/feed2toot |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Ffmpeg](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ffmpeg) | 5.1.2 | https://hub.docker.com/r/linuxserver/ffmpeg |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/filezilla-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Filezilla](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Filezilla) | 3.64.0 | https://filezilla-project.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/firefox-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Firefox](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Firefox) | 114.0.2 | https://firefox-project.org/ |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Fleet](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Fleet) | 2.3.3 | https://hub.docker.com/r/linuxserver/fleet |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/foldingathome-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Foldingathome](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Foldingathome) | 7.6.21 | https://foldingathome.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/freshrss-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Freshrss](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Freshrss) | 1.21.0 | http://freshrss.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/github-desktop-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Github-desktop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Github-desktop) | 3.2.1 | https://hub.docker.com/r/linuxserver/github-desktop |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/gitqlient-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Gitqlient](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Gitqlient) | 1.6.1 | https://hub.docker.com/r/linuxserver/gitqlient |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/grav-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Grav](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Grav) | 1.7.42 | https://github.com/getgrav/grav/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/grocy-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Grocy](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Grocy) | 3.3.2 |  |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/habridge-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Habridge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Habridge) | 5.4.1 | https://github.com/bwssytems/ha-bridge |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/headphones-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Headphones](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Headphones) | version-a78f38c1 | https://github.com/rembo10/headphones |
| <img src="https://raw.githubusercontent.com/healthchecks/healthchecks/master/static/img/welcome.png" width="15"/>&nbsp;&nbsp;&nbsp;[Healthchecks](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Healthchecks) | 2.9.2 | https://hub.docker.com/r/linuxserver/healthchecks |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/hedgedoc.png" width="15"/>&nbsp;&nbsp;&nbsp;[Hedgedoc](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Hedgedoc) | 1.9.8 | https://hedgedoc.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/heimdall-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Heimdall](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Heimdall) | 2.5.6 | https://github.com/linuxserver/Heimdall |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/hishtory-server-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Hishtory-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Hishtory-server) | 0.208.20230623 | https://hub.docker.com/r/linuxserver/hishtory-server |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/linuxserver-ls-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Homeassistant](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Homeassistant) | 2023.6.3 | https://www.home-assistant.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/htpcmanager-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Htpcmanager](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Htpcmanager) | version-1614d863 | https://github.com/Hellowlol/HTPC-Manager |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/jacket-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Jackett](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Jackett) | 0.21.334 | https://github.com/Jackett/Jackett |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/jellyfin-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Jellyfin](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Jellyfin) | 10.8.10 | https://github.com/jellyfin/jellyfin#jellyfin |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Jenkins-builder](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Jenkins-builder) | version-ffe6069e | https://hub.docker.com/r/linuxserver/jenkins-builder |
| <img src="https://kasm-ci.s3.amazonaws.com/kasm_wide.png" width="15"/>&nbsp;&nbsp;&nbsp;[Kasm](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Kasm) | 1.13.0 | https://hub.docker.com/r/linuxserver/kasm |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/kdenlive-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Kdenlive](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Kdenlive) | 421.12.3 | https://hub.docker.com/r/linuxserver/kdenlive |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/lazylibrarian-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Lazylibrarian](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lazylibrarian) | version-f066b525 | https://github.com/DobyTang/LazyLibrarian/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/ldap-auth-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Ldap-auth](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ldap-auth) | 3.4.3 | https://github.com/nginxinc/nginx-ldap-auth |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/libreoffice-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Libreoffice](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Libreoffice) | 7.5.3 | https://www.libreoffice.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/librespeed-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Librespeed](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Librespeed) | 5.2.5 | https://librespeed.electerious.com |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/lidarr.png" width="15"/>&nbsp;&nbsp;&nbsp;[Lidarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lidarr) | 1.1.4 | https://github.com/lidarr/Lidarr |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/limnoria-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Limnoria](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Limnoria) | 2023.5.27 | https://github.com/ProgVal/limnoria |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/lollypop-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Lollypop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lollypop) | 1.4.35 | https://hub.docker.com/r/linuxserver/lollypop |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/lychee-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Lychee](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lychee) | 4.9.4 | https://lychee.electerious.com |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/mariadb-git.png" width="15"/>&nbsp;&nbsp;&nbsp;[Mariadb](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mariadb) | 10.11.4 | https://mariadb.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/mastodon-banner.png" width="15"/>&nbsp;&nbsp;&nbsp;[Mastodon](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mastodon) | 4.1.2 | https://hub.docker.com/r/linuxserver/mastodon |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/medusa-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Medusa](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Medusa) | 1.0.16 | https://github.com/pymedusa/Medusa |
| <img src="https://raw.githubusercontent.com/linuxserver/beta-templates/master/lsiodev/img/minetest-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Minetest](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Minetest) | 5.7.0 | http://www.minetest.net/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/minisatip-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Minisatip](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Minisatip) | version-8d33e939 | https://github.com/catalinii/minisatip |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/mstream-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Mstream](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mstream) | 5.11.4 | https://www.mstream.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/mullvad-browser-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Mullvad-browser](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mullvad-browser) | 12.5.20230627 | https://hub.docker.com/r/linuxserver/mullvad-browser |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/mylar-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Mylar3](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mylar3) | 0.7.2 | https://github.com/mylar3/mylar3 |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/mysql-workbench-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Mysql-workbench](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mysql-workbench) | 8.0.33 | https://www.mysql.com/products/workbench/ |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Nano_logo.png/640px-Nano_logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Nano](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nano) | 21.2.20220522 | https://hub.docker.com/r/linuxserver/nano |
| <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/Nano_logo.png/640px-Nano_logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Nano-wallet](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nano-wallet) | 1.3.2 | https://hub.docker.com/r/linuxserver/nano-wallet |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/netbootxyz.png" width="15"/>&nbsp;&nbsp;&nbsp;[Netbootxyz](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Netbootxyz) | 0.6.8 | https://netboot.xyz/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/netbox-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Netbox](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Netbox) | 3.5.4 | https://github.com/netbox-community/netbox |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/nextcloud-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Nextcloud](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nextcloud) | 27.0.0 | https://nextcloud.com |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/nginx-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Nginx](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nginx) | 1.24.0 | https://www.nginx.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/ngircd-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Ngircd](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ngircd) | version-26.1-r3 | https://ngircd.barton.de/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/nntp2nntp.png" width="15"/>&nbsp;&nbsp;&nbsp;[Nntp2nntp](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nntp2nntp) | 0.3.20221013 | https://github.com/linuxserver/nntp2nntp |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/hydra-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Nzbhydra2](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nzbhydra2) | 5.1.8 | https://github.com/theotherp/nzbhydra2 |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/ombi.png" width="15"/>&nbsp;&nbsp;&nbsp;[Ombi](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ombi) | 4.39.1 | https://www.ombi.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/openssh-server-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Openssh-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Openssh-server) | version-9.3_p1-r3 | https://www.openssh.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/openvscode-server-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Openvscode-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Openvscode-server) | 1.79.2 | https://hub.docker.com/r/linuxserver/openvscode-server |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/opera-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Opera](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Opera) | 100.0.4815 | https://hub.docker.com/r/linuxserver/opera |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/oscam-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Oscam](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Oscam) | version-11719 | http://www.streamboard.tv/oscam/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/overseerr.png" width="15"/>&nbsp;&nbsp;&nbsp;[Overseerr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Overseerr) | 1.33.0 | https://overseerr.dev/ |
| <img src="https://raw.githubusercontent.com/schlagmichdoch/PairDrop/master/public/images/android-chrome-512x512.png" width="15"/>&nbsp;&nbsp;&nbsp;[Pairdrop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pairdrop) | 1.7.6 | https://hub.docker.com/r/linuxserver/pairdrop |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/phpmyadmin-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Phpmyadmin](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Phpmyadmin) | 5.2.1 | https://hub.docker.com/r/linuxserver/phpmyadmin |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/pidgin-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Pidgin](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pidgin) | 2.14.12 | https://hub.docker.com/r/linuxserver/pidgin |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/piwigo-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Piwigo](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Piwigo) | 13.7.0 | http://piwigo.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/plex-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Plex](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Plex) | 1.32.4 | https://www.plex.tv/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/plex-meta-manager-banner.png" width="15"/>&nbsp;&nbsp;&nbsp;[Plex-meta-manager](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Plex-meta-manager) | 1.19.0 | https://hub.docker.com/r/linuxserver/plex-meta-manager |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/projectsend-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Projectsend](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Projectsend) | version-r1605 | http://www.projectsend.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/prowlarr-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Prowlarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Prowlarr) | 1.6.3 | https://github.com/Prowlarr/Prowlarr |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/pwndrop-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Pwndrop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pwndrop) | 1.0.1 | https://github.com/kgretzky/pwndrop |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/pydio-cells-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Pydio-cells](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pydio-cells) | 4.2.3 | https://pydio.com/ |
| <img src="https://pyload.net/img/banner.png" width="15"/>&nbsp;&nbsp;&nbsp;[Pyload-ng](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pyload-ng) | 0.5.0 | https://hub.docker.com/r/linuxserver/pyload-ng |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/cloud9-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Pylon](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pylon) | 2.9.0 | https://github.com/pylonide/pylon |
| <img src="https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/qbittorrent-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Qbittorrent](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Qbittorrent) | 4.5.4 | https://www.qbittorrent.org |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/qdirstat-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Qdirstat](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Qdirstat) | 1.8.1 | https://hub.docker.com/r/linuxserver/qdirstat |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/quassel-core-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Quassel-core](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Quassel-core) | 0.14.0 | http://quassel-irc.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/quassel-web-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Quassel-web](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Quassel-web) | version-20880f2c | https://github.com/magne4000/quassel-webserver |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/radarr.png" width="15"/>&nbsp;&nbsp;&nbsp;[Radarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Radarr) | 4.5.2 | https://github.com/Radarr/Radarr |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/raneto.png" width="15"/>&nbsp;&nbsp;&nbsp;[Raneto](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Raneto) | 0.17.5 | http://raneto.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/rdesktop.png" width="15"/>&nbsp;&nbsp;&nbsp;[Rdesktop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Rdesktop) | ubuntu-mate-version-217061ed | https://hub.docker.com/r/linuxserver/rdesktop |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Readme-sync](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Readme-sync) | version-4f3ce0a3 | https://hub.docker.com/r/linuxserver/readme-sync |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/remmina-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Remmina](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Remmina) | 1.4.2 | https://remmina.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/requestrr.png" width="15"/>&nbsp;&nbsp;&nbsp;[Requestrr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Requestrr) | 2.1.2 | https://github.com/darkalfx/requestrr |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/resilio.png" width="15"/>&nbsp;&nbsp;&nbsp;[Resilio-sync](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Resilio-sync) | 2.7.3 | https://www.resilio.com/individuals/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/rsnapshot.png" width="15"/>&nbsp;&nbsp;&nbsp;[Rsnapshot](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Rsnapshot) | 1.4.5 | https://www.rsnapshot.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/sabnzbd-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Sabnzbd](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sabnzbd) | 4.0.2 | http://sabnzbd.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/sickchill-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Sickchill](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sickchill) | 2023.6.27 | https://sickchill.github.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/sickgear-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Sickgear](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sickgear) | 3.29.4 | https://github.com/SickGear/SickGear |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/smokeping-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Smokeping](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Smokeping) | 2.8.2 | http://oss.oetiker.ch/smokeping/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/snapdrop-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Snapdrop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Snapdrop) | version-eac78009 | https://github.com/RobinLinus/snapdrop |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/snipe-it-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Snipe-it](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Snipe-it) | 6.1.1 | https://github.com/snipe/snipe-it |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/sonarr-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Sonarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sonarr) | 3.0.10 | https://sonarr.tv/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/sqlitebrowser-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Sqlitebrowser](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sqlitebrowser) | 3.12.2 | https://sqlitebrowser.org/ |
| <img src="https://github.com/linuxserver/docker-templates/raw/master/linuxserver.io/img/swag.gif" width="15"/>&nbsp;&nbsp;&nbsp;[Swag](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Swag) | 2.6.0 | https://docs.linuxserver.io/general/swag |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/synclounge-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Synclounge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Synclounge) | 5.2.5 | https://github.com/samcm/synclounge |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/syncthing-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Syncthing](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Syncthing) | 1.23.5 | https://github.com/syncthing/syncthing |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/syslog-ng-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Syslog-ng](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Syslog-ng) | 4.1.1 | https://hub.docker.com/r/linuxserver/syslog-ng |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/tautulli-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Tautulli](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Tautulli) | 2.12.4 | http://tautulli.com/ |
| <img src="https://avatars3.githubusercontent.com/u/12324908?s=200&v=4" width="15"/>&nbsp;&nbsp;&nbsp;[Tester](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Tester) | version-66f677b0 | https://hub.docker.com/r/linuxserver/tester |
| <img src="https://raw.githubusercontent.com/linuxserver/community-templates/master/lsiocommunity/img/shout-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Thelounge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Thelounge) | 4.4.1 | https://thelounge.github.io/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/transmission.png" width="15"/>&nbsp;&nbsp;&nbsp;[Transmission](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Transmission) | 4.0.3 | http://www.transmissionbt.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/tvheadend-big.png" width="15"/>&nbsp;&nbsp;&nbsp;[Tvheadend](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Tvheadend) | version-7b5c5269 | https://www.tvheadend.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/ubooquity-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Ubooquity](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ubooquity) | 2.1.2 | https://vaemendis.net/ubooquity/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/unifi-controller-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Unifi-controller](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Unifi-controller) | 7.4.156 | https://www.ui.com/software/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/vscodium-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Vscodium](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Vscodium) | 1.79.2 | https://hub.docker.com/r/linuxserver/vscodium |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/webcord-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Webcord](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Webcord) | 4.3.0 | https://hub.docker.com/r/linuxserver/webcord |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/webgrabplus.png" width="15"/>&nbsp;&nbsp;&nbsp;[Webgrabplus](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Webgrabplus) | 5.0.1 | http://webgrabplus.com/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/webtop-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Webtop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Webtop) | ubuntu-xfce-version-7a58a756 | https://github.com/linuxserver/docker-webtop |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/wikijs-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Wikijs](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wikijs) | 2.5.299 | https://wiki.js.org/ |
| <img src="https://www.wireguard.com/img/wireguard.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Wireguard](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wireguard) | 1.0.20210914 | https://hub.docker.com/r/linuxserver/wireguard |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/wireshark-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Wireshark](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wireshark) | 4.0.6 | https://www.wireshark.org/ |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/wps-office-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Wps-office](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wps-office) | version-7a0c9461 | https://hub.docker.com/r/linuxserver/wps-office |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/xbackbone-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Xbackbone](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Xbackbone) | 3.6.3 | https://github.com/SergiX44/XBackBone |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/your_spotify-logo.png" width="15"/>&nbsp;&nbsp;&nbsp;[Your_spotify](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Your_spotify) | 1.6.0 | https://hub.docker.com/r/linuxserver/your_spotify |
| <img src="https://cdn.jsdelivr.net/gh/WisdomSky/CasaOS-LinuxServer-AppStore@main/default-icon.svg" width="15"/>&nbsp;&nbsp;&nbsp;[Yq](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Yq) | 3.2.2 | https://hub.docker.com/r/linuxserver/yq |
| <img src="https://raw.githubusercontent.com/linuxserver/docker-templates/master/linuxserver.io/img/znc-icon.png" width="15"/>&nbsp;&nbsp;&nbsp;[Znc](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Znc) | 1.8.2 | http://wiki.znc.in/ZNC |



## 💡 Frequently Asked Questions

### 👉 How to Upgrade CasaOS

Run the following command:

    curl -fsSL https://get.casaos.io/update/v0.4.4-alpha | sudo bash


### 👉 Error 404 Not Found during install

This could be caused by your CasaOS running on a port other than the default `port 80`. You need to add the `-u` flag at the end to tell command which port your CasaOS is running:

```bash
casaos-cli app-management register app-store https://casaos-appstore.paodayag.dev/linuxserver.zip -u "localhost:<my-casa-os-port>"
```

Replace `<my-casa-os-port>` with the port where your CasaOS is running. For example if my CasaOS is running on port 99:

```bash
casaos-cli app-management register app-store https://casaos-appstore.paodayag.dev/linuxserver.zip -u "localhost:99"
```

### 👉 How to uninstall the LinuxServer Appstore

Get the assigned ID of the LinuxServer Appstore:

    casaos-cli app-management list app-stores

Unregister the LinuxServer Appstore:

    casaos-cli app-management unregister app-store <linuxserver-appstore-id>

> NOTE: Replace <linuxserver-appstore-id> with the corresponding ID of the LinuxServer Appstore.

---


## Acknowledgements
* [technorabilia](https://github.com/technorabilia)

---

## Contributing

Contributing to this Appstore is temporarily not possible at the moment. Please refrain from submitting PRs into this repository.

This repository is auto-generated by a separate tool [CasaOS-Balhin](https://github.com/WisdomSky/CasaOS-Balhin/tree/linuxserver), we will publicize it in the near future to allow the community to make changes to this appstore.

We are still currently in the process of revamping the tool to make adding conttributions easier.

Please watch out as we open it to the public in the future.

---

Generated with ❤️ using [CasaOS-Balhin](https://github.com/WisdomSky/CasaOS-Balhin/tree/linuxserver)