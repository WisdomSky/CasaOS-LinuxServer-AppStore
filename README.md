
![CasaOS LinuxServer AppStore](https://raw.githubusercontent.com/WisdomSky/CasaOS-LinuxServer-AppStore/main/banner.png)

# CasaOS LinuxServer AppStore

A CasaOS custom Appstore containing over 100+ [LinuxServer.io](https://www.linuxserver.io/) images.




## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [List of Applications](#list-of-applications)
- [Frequently Asked Questions / FAQs](#frequently-asked-questions)
    - [How to Upgrade CasaOS](#how-to-upgrade-casaos)
    - ["Error 404: Not Found" during install](#error-404-not-found-during-install)
    - [How to uninstall the LinuxServer Appstore](#how-to-uninstall-the-linuxserver-appstore)
- [Contributing](#contributing)

---

## Introduction

The **LinuxServer AppStore** is a custom appstore built to work for [CasaOS](https://github.com/IceWhaleTech/CasaOS).

This custom appstore for CasaOS contains a wide variety of configurations of docker images built and maintained by the [linuxserver.io](https://www.linuxserver.io/) community which are adapted to work for CasaOS.

The LinuxServer Appstore is **guaranteed to provide you the latest version of every Application** as the appstore automatically tracks new releases and updates the contents of this repository daily.


---


## Installation

Run the following command to install the appstore:
```bash
casaos-cli app-management register app-store https://casaos-appstore.paodayag.dev/linuxserver.zip
```

> **NOTE: Custom Appstore is only supported on CasaOS version [0.4.4](https://blog.casaos.io/blog/23.html) and above. How to upgrade? [Click here](#how-to-upgrade-casaos)**

---

## List of Applications

* [Adguardhome-sync](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Adguardhome-sync) 0.4.14
* [Airsonic-advanced](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Airsonic-advanced) 11.0.0
* [Apprise-api](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Apprise-api) 0.9.2
* [Audacity](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Audacity) 3.3.3
* [Babybuddy](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Babybuddy) 1.16.0
* [Bazarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Bazarr) 1.2.2
* [Beets](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Beets) 1.6.0
* [Blender](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Blender) 3.5.1
* [Boinc](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Boinc) 7.20.5
* [Booksonic-air](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Booksonic-air) 2201.1.0
* [Bookstack](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Bookstack) 23.05.2
* [Budge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Budge) 0.0.9
* [Build-agent](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Build-agent) version-cb7b1264
* [Calibre](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Calibre) 6.21.0
* [Calibre-web](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Calibre-web) 0.6.20
* [Changedetection.io](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Changedetection.io) 0.43.20230621
* [Chromium](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Chromium) version-bc4a2ac5
* [Ci](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ci) version-fff183d3
* [Code-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Code-server) 4.14.0
* [Cops](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Cops) 1.1.3
* [Daapd](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Daapd) 28.6.20230621
* [Darktable](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Darktable) 4.0.1
* [Davos](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Davos) 2.2.2
* [Ddclient](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ddclient) 3.10.0
* [Deluge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Deluge) 2.1.1
* [Digikam](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Digikam) version-2023-04-21
* [Dillinger](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Dillinger) 3.39.1
* [Diskover](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Diskover) 2.1.0
* [Dokuwiki](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Dokuwiki) version-2023-04-04a
* [Domoticz](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Domoticz) 2023.1.20230615
* [Doplarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Doplarr) 3.6.2
* [Doublecommander](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Doublecommander) version-56ac29f5
* [Duckdns](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Duckdns) version-45e56094
* [Duplicati](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Duplicati) 2.0.7
* [Emby](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Emby) 4.7.13
* [Embystat](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Embystat) 0.2.0
* [Emulatorjs](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Emulatorjs) 1.7.2
* [Endlessh](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Endlessh) version-dfe44eb2
* [Fail2ban](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Fail2ban) 1.0.2
* [Feed2toot](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Feed2toot) 0.17.20230624
* [Ffmpeg](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ffmpeg) 5.1.2
* [Filezilla](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Filezilla) 3.64.0
* [Firefox](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Firefox) 114.0.2
* [Fleet](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Fleet) 2.3.3
* [Foldingathome](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Foldingathome) 7.6.21
* [Freshrss](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Freshrss) 1.21.0
* [Github-desktop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Github-desktop) 3.2.1
* [Gitqlient](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Gitqlient) 1.6.1
* [Grav](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Grav) 1.7.42
* [Grocy](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Grocy) 3.3.2
* [Habridge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Habridge) 5.4.1
* [Headphones](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Headphones) version-a78f38c1
* [Healthchecks](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Healthchecks) 2.9.2
* [Hedgedoc](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Hedgedoc) 1.9.8
* [Heimdall](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Heimdall) 2.5.6
* [Hishtory-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Hishtory-server) 0.208.20230623
* [Homeassistant](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Homeassistant) 2023.6.3
* [Htpcmanager](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Htpcmanager) version-1614d863
* [Jackett](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Jackett) 0.21.294
* [Jellyfin](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Jellyfin) 10.8.10
* [Jenkins-builder](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Jenkins-builder) version-ffe6069e
* [Kasm](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Kasm) 1.13.0
* [Kdenlive](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Kdenlive) 421.12.3
* [Lazylibrarian](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lazylibrarian) version-f066b525
* [Ldap-auth](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ldap-auth) 3.4.3
* [Libreoffice](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Libreoffice) 7.5.3
* [Librespeed](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Librespeed) 5.2.5
* [Lidarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lidarr) 1.1.4
* [Limnoria](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Limnoria) 2023.5.27
* [Lollypop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lollypop) 1.4.35
* [Lychee](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Lychee) 4.9.2
* [Mariadb](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mariadb) 10.11.4
* [Mastodon](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mastodon) 4.1.2
* [Medusa](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Medusa) 1.0.16
* [Minetest](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Minetest) 5.7.0
* [Minisatip](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Minisatip) version-8d33e939
* [Mstream](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mstream) 5.11.4
* [Mullvad-browser](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mullvad-browser) 12.0.7
* [Mylar3](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mylar3) 0.7.2
* [Mysql-workbench](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Mysql-workbench) 8.0.33
* [Nano](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nano) 21.2.20220522
* [Nano-wallet](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nano-wallet) 1.3.2
* [Netbootxyz](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Netbootxyz) 0.6.8
* [Netbox](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Netbox) 3.5.4
* [Nextcloud](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nextcloud) 27.0.0
* [Nginx](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nginx) 1.24.0
* [Ngircd](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ngircd) version-26.1-r3
* [Nntp2nntp](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nntp2nntp) 0.3.20221013
* [Nzbhydra2](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Nzbhydra2) 5.1.8
* [Ombi](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ombi) 4.39.1
* [Openssh-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Openssh-server) version-9.3_p1-r3
* [Openvscode-server](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Openvscode-server) 1.79.2
* [Opera](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Opera) 100.0.4815
* [Oscam](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Oscam) version-11719
* [Overseerr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Overseerr) 1.33.0
* [Pairdrop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pairdrop) 1.7.6
* [Phpmyadmin](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Phpmyadmin) 5.2.1
* [Pidgin](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pidgin) 2.14.12
* [Piwigo](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Piwigo) 13.7.0
* [Plex](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Plex) 1.32.4
* [Plex-meta-manager](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Plex-meta-manager) 1.19.0
* [Projectsend](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Projectsend) version-r1605
* [Prowlarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Prowlarr) 1.5.2
* [Pwndrop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pwndrop) 1.0.1
* [Pydio-cells](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pydio-cells) 4.2.2
* [Pyload-ng](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pyload-ng) 0.5.0
* [Pylon](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Pylon) 2.9.0
* [Qbittorrent](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Qbittorrent) 4.5.4
* [Qdirstat](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Qdirstat) 1.8.1
* [Quassel-core](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Quassel-core) 0.14.0
* [Quassel-web](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Quassel-web) version-20880f2c
* [Radarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Radarr) 4.5.2
* [Raneto](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Raneto) 0.17.5
* [Rdesktop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Rdesktop) arch-icewm-version-2023-06-23
* [Readme-sync](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Readme-sync) version-90b0ec76
* [Remmina](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Remmina) 1.4.2
* [Requestrr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Requestrr) 2.1.2
* [Resilio-sync](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Resilio-sync) 2.7.3
* [Rsnapshot](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Rsnapshot) 1.4.5
* [Sabnzbd](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sabnzbd) 4.0.2
* [Sickchill](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sickchill) 2023.5.30
* [Sickgear](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sickgear) 3.29.4
* [Smokeping](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Smokeping) 2.8.2
* [Snapdrop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Snapdrop) version-eac78009
* [Snipe-it](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Snipe-it) 6.1.1
* [Sonarr](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sonarr) 3.0.10
* [Sqlitebrowser](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Sqlitebrowser) 3.12.2
* [Swag](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Swag) 2.6.0
* [Synclounge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Synclounge) 5.2.5
* [Syncthing](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Syncthing) 1.23.5
* [Syslog-ng](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Syslog-ng) 4.1.1
* [Tautulli](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Tautulli) 2.12.4
* [Tester](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Tester) version-66f677b0
* [Thelounge](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Thelounge) 4.4.1
* [Transmission](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Transmission) 4.0.3
* [Tvheadend](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Tvheadend) version-7b5c5269
* [Ubooquity](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Ubooquity) 2.1.2
* [Unifi-controller](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Unifi-controller) 7.4.156
* [Vscodium](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Vscodium) 1.79.2
* [Webcord](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Webcord) 4.3.0
* [Webgrabplus](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Webgrabplus) 5.0.1
* [Webtop](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Webtop) fedora-i3-version-d48c501c
* [Wikijs](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wikijs) 2.5.299
* [Wireguard](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wireguard) 1.0.20210914
* [Wireshark](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wireshark) 4.0.6
* [Wps-office](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Wps-office) version-3fddab77
* [Xbackbone](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Xbackbone) 3.6.3
* [Your_spotify](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Your_spotify) 1.6.0
* [Yq](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Yq) 3.2.2
* [Znc](https://github.com/WisdomSky/CasaOS-LinuxServer-AppStore/tree/main/Apps/Znc) 1.8.2



## Frequently Asked Questions

### How to Upgrade CasaOS

Run the following command:

    curl -fsSL https://get.casaos.io/update/v0.4.4-alpha | sudo bash


### Error 404 Not Found during install

This could be caused by your CasaOS running on a port other than the default `port 80`. You need to add the `-u` flag at the end to tell command which port your CasaOS is running:

```bash
casaos-cli app-management register app-store https://casaos-appstore.paodayag.dev/linuxserver.zip -u "localhost:<my-casa-os-port>"
```

Replace `<my-casa-os-port>` with the port where your CasaOS is running. For example if my CasaOS is running on port 99:

```bash
casaos-cli app-management register app-store https://casaos-appstore.paodayag.dev/linuxserver.zip -u "localhost:99"
```

### How to uninstall the LinuxServer Appstore

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