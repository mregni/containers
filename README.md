# pichu-docker-network

![](https://img.shields.io/:Other-2ecc71.svg?style=for-the-badge)
![](https://img.shields.io/:Media-1081C2.svg?style=for-the-badge)
![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge)
![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge)
![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge)
![](https://img.shields.io/:Gaming-F56EB2.svg?style=for-the-badge)
![](https://img.shields.io/:Coding-A0A227.svg?style=for-the-badge)
![](https://img.shields.io/:Database-98C6F4.svg?style=for-the-badge)
![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge)
![](https://img.shields.io/:Social-4ecad8.svg?style=for-the-badge)
![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge)
![](https://img.shields.io/:Security-d8cd4e.svg?style=for-the-badge)




## Standalone services
|   | Name |  Description | Type | Docker container | Extra info | Used by |
|---|---|---|---|---|---|---|
|  <img src="images/bitwarden.png" width="50"> | BitWarden | Password manager | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `bitwarden/server` | [Install](https://bitwarden.com/help/install-on-premise-linux/) | 
|  <img src="images/107590253e667ae1e3267d49334d298648a450cf88eecd96c6b0b3d3cf36f16e.png" width="50">  |  BOINC | Science research | ![](https://img.shields.io/:Other-2ecc71.svg?style=for-the-badge)  | `linuxserver/boinc` |  |
|  <img src="images/81359dfa9b0d272010254bb97635f7c121a010c4a1d6b56057256bd02d17a4f0.png" width="50"> |  Emby | Media server | ![](https://img.shields.io/:Media-1081C2.svg?style=for-the-badge) | `emby/embyserver`  |
| <img src="images/bd5570ce87dc9a43d8d6bd2f801e9535850ffa4c304eab768bd446b9cf2009b7.png" width="50"> |  Gitea | Git server | ![](https://img.shields.io/:Coding-A0A227.svg?style=for-the-badge) | `gitea/gitea` |  |
|  <img src="images/c91d029a4a55439caa0ea551bb6f40cb6e04a61c3139570c30e4d63d2416ef7f.png" width="50"> |  Gotify | PUSH notifications | ![](https://img.shields.io/:Social-4ecad8.svg?style=for-the-badge) | `gotify/server` |  |
|  <img src="images/422a3ecca2cd2d5afb8f8536f5eba121a0b1c58be5f8477bc84439f13b76663f.png" width="50"> |  Heimdall | Private dashboard | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `linuxserver/heimdall` |  |
|  <img src="images/971f857cae7af4b29cc906ace2238c1617777a4d07cfe9608295e490cf835e56.png" width="50"> |  No-Ip | No-ip service | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `uping/no-ip` |  |
|  <img src="images/c5073d4016602047187b5c622153f2d3607450c74683dfee48b7da17907e99c3.png" width="50"> |  Portainer | Docker container management | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `portainer/portainer-ce`  |  |
| <img src="images/2e7e854d1d223e7aa53d3db4ffacdb587815a38314c026f4e0e66a9a9a465845.png" width="50">  |  Traefik | Reverse proxy | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `traefik` |  |
| <img src="images/2e7e854d1d223e7aa53d3db4ffacdb587815a38314c026f4e0e66a9a9a465845.png" width="50"> | Treafik cert dumper | Dumps Let's Encrypt certificates | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `humenius/traefik-certs-dumper` | [Install](https://github.com/ldez/traefik-certs-dumper/blob/master/docs/docker-compose-traefik-v2.yml) |  |
|  | Error pages | Custom error pages | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `tarampampam/error-pages` | [Install](https://doc.traefik.io/traefik/middlewares/http/errorpages/) <br />[GitHub](https://github.com/tarampampam/error-pages) |  |
| <img src="images/93f47203d1ebe335e33d6e56db62169040f42a039a5078b324f05f7ae91cb27e.png" width="50">  |  Valheim | Valheim server | ![](https://img.shields.io/:Gaming-F56EB2.svg?style=for-the-badge) | `mbround18/valheim` |  |
|  <img src="images/bba0fd82aa6f0d22e55608f60b7e658999075a9d1524a1d07da0cdc4a4101749.png" width="50"> |  Watchtower | Auto docker updater | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `containrrr/watchtower` |  |
|  <img src="images/50076cf5f94513b4252488d999a4315c9109030fd2a72ec22039e5f074fea5f0.png" width="50"> |  Wireguard | VPN server | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `linuxserver/wireguard` |  |
| <img src="images/848fe3ba3522491157d2eea1aa5bc27249004a4f1a7166f3980a348b2960b96d.png" width="50"> | PostGreSQL | SQL database | ![](https://img.shields.io/:Database-98C6F4.svg?style=for-the-badge) | `postgres` | | Gotify, <br />Nextcloud, <br />Joplin, <br />Wiki.js, <br />Guacamole, <br />Peppermint |
| <img src="images/d55459f89b72d3f979fde7edf0979babe5e03afc716f8bf23741fcc1502784cc.png" width="50"> | Conreq | Content requester | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `conreq` | [Install](https://github.com/Archmonger/Conreq) |  |
| <img src="images/8f9dee4f958a9b10358814b2cf311a9a60b424ce73446e7a16f5bfa680b0a25f.png" width="50"> | Radarr | Movie downloader | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `linuxserver/radarr` |  | Requestrr |
| <img src="images/9b5a08e4b16c1a6d8e83e084f2ffb682a292d2684b435fa14ad5d40c89be153a.png" width="50"> | Sonarr | TV show downloader | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `linuxserver/sonarr` |  | Requestrr |
| <img src="images/4a75e5cf7677202fbb186b48a27656aaba23b5965b03abc02318ef33e91dc80d.png" width="50"> | NZBGet | NZB downloader | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `linuxserver/nzbget` |  |  |
| <img src="images/6992789f8ebc0cc362047df4c6101971c1a670d275b5768c9bd0583aed2e598d.png" width="50"> | Prowlarr | Indexer manage |  ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `linuxserver/prowlarr` |  |  |
| <img src="images/383947572429a0a46fe73c47190ab6e989fbc8649da047777f4fb90a4660f777.png" width="50"> | qflood | QBittorrent and Flood UI | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `cr.hotio.dev/hotio/qflood` | [Hotio](https://hotio.dev/containers/qflood/) |  |
| <img src="images/b2a7822dbfd86e701619a6ef2f0e72928b3963b747a5531a7933dac09d239e74.png" width="50"> | Requestrr | Request chat bot  | ![](https://img.shields.io/:Social-4ecad8.svg?style=for-the-badge) | `linuxserver/requestrr` | [Github](https://github.com/darkalfx/requestrr) |  |
| <img src="images/b5fcc5f7f5ad8e9e0cb42d09fb6d779514b163f5c1713ab0c89f12833a1f83b7.png" width="50"> | Tdarr | Distributed Transcoding System | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `ghcr.io/haveagitgat/tdarr` `ghcr.io/haveagitgat/tdarr_node` | [Install](https://docs.tdarr.io/docs/installation/docker/run-compose/) |  |
| <img src="images/08ab299236987dbda6ef26eb8b4960180b5744ac40fea1888f5a9ac465a6b89e.png" width="50"> | Nextcloud | Private file hosting | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `nextcloud:apache` | [Install](https://hub.docker.com/_/nextcloud) |  |
| <img src="images/793b77919fbf6fc99774ba8572f851398d2390909fa4753548cc9d37b2183f02.png" width="50"> | Redis | Caching DB  | ![](https://img.shields.io/:Database-98C6F4.svg?style=for-the-badge) | `redis:alpine` |  | Nextcloud |
| <img src="images/08ab299236987dbda6ef26eb8b4960180b5744ac40fea1888f5a9ac465a6b89e.png" width="50"> | Nextcloud cronjob | Nextcloud cron job | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `rcdailey/nextcloud-cronjob` |  | Nextcloud |
| <img src="images/b187d2883b767fb4d1afacfa784653539c4aaf2191f103cecd740bb7b9a14d67.png" width="50"> | Node exporter | Unix metric exporter | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) | `quay.io/prometheus/node-exporter` | [Install](https://prometheus.io/docs/guides/node-exporter/) | Prometheus |
| <img src="images/b187d2883b767fb4d1afacfa784653539c4aaf2191f103cecd740bb7b9a14d67.png" width="50"> | Node exporter | Windows metric exporter | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) |  | [Github](https://github.com/prometheus-community/windows_exporter) | Prometheus |
| <img src="images/b187d2883b767fb4d1afacfa784653539c4aaf2191f103cecd740bb7b9a14d67.png" width="50"> | Node Exporter | NVidia metric exporter | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) |  | [Github](https://github.com/NVIDIA/dcgm-exporter) | Prometheus |
| <img src="images/7a74bf766c7d1599851d9bafa8d371712c556bc715c02e7934a6ed41f5f7e33d.png" width="50"> | Prometheus | System metric logger | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) | ` prom/prometheus` | [Install](https://prometheus.io/docs/prometheus/latest/installation/) | Grafana |
| <img src="images/7a74bf766c7d1599851d9bafa8d371712c556bc715c02e7934a6ed41f5f7e33d.png" width="50"> | Prom alert mananger | Managing prometheus alerts | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `prom/alertmanager` |  | Discord alert |
| <img src="images/80a143f2ef8e1c0c073c2a4714e4910873356872af555ac144e9231b71e08dcb.png" width="50"> | cAdvisor | Container resource monitor | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) | `gcr.io/cadvisor/cadvisor` |  | Grafana |
| <img src="images/cfda5fc4fdbe063c5bdf5988342b185626fa4eb4afa1658123ca2afef4c33f83.png" width="50"> | Grafana | Metric dashboards | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `grafana/grafana` |  |  |
| <img src="images/d48d01f0befeae577bdd6bd9f9b8c1e54e32b406d7db57f44d75730e27a2124e.png" width="50"> | Discord alert manager | Pushes alerts to Discord | ![](https://img.shields.io/:Social-4ecad8.svg?style=for-the-badge) | `benjojo/alertmanager-discord` |  |  |
| <img src="images/5d05dbd81f85f3ca34f77d8d0007c1fca70b852658bb5bd25b24e75c2dae7717.png" width="50"> | QdirStat | Directory statistics | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `linuxserver/qdirstat` | [Github](https://github.com/linuxserver/docker-qdirstat) |  |
| <img src="images/0b5b012afedb70cf1a92acbac343807623eba65923ee009cc42f9c87347e7199.png" width="50"> | Netbox | Network admin tool | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `linuxserver/netbox` | [Github](https://github.com/netbox-community/netbox) |  |
| <img src="images/81bc4a65807bb047614625894fadd2bbeea33c994cd7cc1f4eb941e90cbb49d0.png" width="50"> | Uptime kuma | Uptime dashboard | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) | `louislam/uptime-kuma` | [Github](https://github.com/louislam/uptime-kuma) |  |
| <img src="images/4af209497b07e0fd060b4813cd6bba7589346815ec7c139a5bf27470a2e379eb.png" width="50"> | Scrutiny | S.M.A.R.T monitoring | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) | `linuxserver/scrutiny` |  |  |
| <img src="images/1384bfb145ac92e315e19a941d32799b7313f7da21f8d20c68a7eaf2d177a116.png" width="50"> | NetData | Full system monitoring | ![](https://img.shields.io/:Monitoring-D8B125.svg?style=for-the-badge) | `netdata/netdata` | [Install](https://learn.netdata.cloud/docs/agent/packaging/docker) |  |
| <img src="images/4921b7fc44957ee94ccf716d8163997a66710a2b2426bfe119f004df6acb1eb0.png" width="50"> | Paperless NG | Scanned document storage | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `jonaswinkler/paperless-ng` |  |  |
| <img src="images/2d658a9d4087717ff08793651e8383e633ab18dfe4665d81a9f8ad95b14fab75.png" width="50"> | Joplin | Note taking app | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `joplin/server` | [Install](https://hub.docker.com/r/joplin/server) [Website](https://joplinapp.org/) |  |
| <img src="images/55503a29b41d230ef9ed8bb9b62fa6e86a65bf23479036b3ff2edae6798be396.png" width="50"> | SnapDrop | Drop and upload file service | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `linuxserver/snapdrop` | [Install](https://hub.docker.com/r/linuxserver/snapdrop) <br />[Website](https://github.com/RobinLinus/snapdrop) |  |
| <img src="images/a165b5f9f7e7fc2d83a06b27851b48819113ba731b9b5137ee1aa3be4605d59e.png" width="50"> | Wiki.js | Wiki pages | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `ghcr.io/requarks/wiki` | [Install](https://docs.requarks.io/install/docker) |  |
|  | Dozzle | Log viewer | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `amir20/dozzle` | [Github](https://github.com/amir20/dozzle) |  |
| <img src="images/937aba53f6f821a2cbe584a667d0f5ed0f6708003334132ae86d80a97b273203.png" width="50"> | Guacamole | Browser based RDP | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `guacamole/guacamole` | [DockerHub](https://hub.docker.com/r/guacamole/guacamole) |  |
|  | Docker cleanup script | Cleanup unused containers and images | ![](https://img.shields.io/:System-D7624B.svg?style=for-the-badge) | `clockworksoul/docker-gc-cron` | [DockerHub](https://hub.docker.com/r/clockworksoul/docker-gc-cron) |  |
| <img src="images/eb21ab2f8f56b8872e60d12434f01dacdedf14a68333e1a32b440801844b361a.png" width="50"> | Authelia | SSO login page | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `authelia/authelia` | [Install](https://www.smarthomebeginner.com/docker-authelia-tutorial/) |  |
| <img src="images/a83bdc29a89220ac897c754cf32c9de54b471e2cc943bc47b949efc10027dc06.png" width="50"> | Wazuh | Security monitoring (needs agents) | ![](https://img.shields.io/:Security-d8cd4e.svg?style=for-the-badge) | `wazuh/wazuh-manager` | [Install](https://documentation.wazuh.com/current/docker/wazuh-container.html)<br /> [Website](https://wazuh.com/) <br />[GitHub](https://github.com/wazuh/wazuh-docker) <br />[DockerHub](https://hub.docker.com/u/wazuh)|  |
| <img src="images/82a13f51babd30e7bfa16ac34a1dd740b5181f7f706d2f0bcdd5c53da24e4a49.png" width="50"> | AdGuard | Ad blocking | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `adguard/adguardhome` | [Website](https://adguard.com/) |  |
| <img src="images/aafa77f104399f46d6eb17f47491d04c74fe15ff35e4d1eb5295372d896d8044.png" width="50"> | Sqlite Browser | Sqlite HTML browser | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `linuxserver/sqlitebrowser` | [DockerHub](https://hub.docker.com/r/linuxserver/sqlitebrowser) |  |
| <img src="images/7f93c61521a77f7b69130e064c59f947803759ad0d2cbc3e2fc601fc19cbd570.png" width="50"> | Darktable | Photography workflow application | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `linuxserver/darktable` | [DockerHub](https://hub.docker.com/r/linuxserver/darktable)<br /> [Website](https://www.darktable.org/) |  |
| <img src="images/be4d2805c9db9a19ec1e5d21661d70e6df59327f6a685bb600c45c6667b6980e.png" width="50"> | Invidious | Youtube front-end | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `quay.io/invidious/invidious` | [Install](https://docs.invidious.io/Installation/#docker-compose-method-production) |  |
| <img src="images/5f6f233b965cf6dbe5e5dfed2847535b8c10f2bf19382c47607d7d9721073e18.png" width="50"> | Grocy | ERP beyond your fridge | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `linuxserver/grocy` | [Website](https://grocy.info/) |  |
| <img src="images/94e627adccc66b5d854c183fbb2bb9b18d577b052be64246497c692ec2ec17e9.png" width="50"> | Peppermint | Ticket Management System |  ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `pepperlabs/peppermint` | [Install](https://docs.peppermint.sh/) |  |
| <img src="images/f4a2f9d3c8b5182be6d561b68357d54c4dea6a0043fb09803c499253413f5cf6.png" width="50"> | Firefly III | Personal finance manager  | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `fireflyiii/core` | [Install](https://docs.firefly-iii.org/firefly-iii/installation/docker/) |  |
| <img src="images/174e95c25f578e505fa687f3c02b600196ddbe2b7d3d72b02785deebc12bb18f.png" width="50"> | Matomo | Website analytics | ![](https://img.shields.io/:Tooling-8B36DA.svg?style=for-the-badge) | `matomo` | [Website](https://matomo.org/) |  |
| <img src="images/96b5a62c725a78a211943dcc0740f7a8d80c4c5b51a2f741f0b2314216fafc77.png" width="50"> | RxResu | Reactive CV | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) | `amruthpillai/reactive-resume` | [Website](https://rxresu.me/) |  |
| <img src="images/eda6ffbf2aa562b04e261e7d72ff5fffb9fc945ae98ebcd10a5ec4f903106b0f.png" width="50"> | mariaDb  | Maria database  | ![](https://img.shields.io/:Database-98C6F4.svg?style=for-the-badge) | `mariadb` |  | Matomo |
| <img src="images/da7afc97cc8ed44b6975d3b5730fdd001fb480c6b9a788f1d92b0da789572513.png" width="50"> | Fail2Ban | IP banning | ![](https://img.shields.io/:Security-d8cd4e.svg?style=for-the-badge) | `crazymax/fail2ban` | [Install](https://arvind.io/posts/using-fail2ban-to-protect-exposed-services/) |  |
| <img src="images/5fb8a6072ab7e96e83ed0c731e5554667595beda936bd9957d8221de9d4eb30c.png" width="50"> | Habitica | Gaminfy | ![](https://img.shields.io/:Office-4fd66c.svg?style=for-the-badge) |  | [Install](https://habitica.fandom.com/wiki/Setting_up_Habitica_Locally_on_Docker) |  |
| <img src="images/d3d131a63419f8d1b24a651d067d3efc5db8d2d24be2364a8b95f8ca667c7cd7.png" width="50"> | Bazarr | Subtitle downloader | ![](https://img.shields.io/:Download-d84e4e.svg?style=for-the-badge) | `linuxserver/bazarr` |  |  |


## Duplicate service to check
Containers that need checking for duplication or really needed.
### Monitoring
- Statping: [https://hub.docker.com/r/hunterlong/statping](https://hub.docker.com/r/hunterlong/statping)
- Cockpit: [https://cockpit-project.org/](https://cockpit-project.org/)

### Server management
- Remmina: [https://remmina.org/](https://remmina.org/) => Remote access screen and file sharing to your desktop.
- APC UPS Management: [https://github.com/gersilex/apcupsd-docker](https://github.com/gersilex/apcupsd-docker)

### Auth
- OAuth: [https://hub.docker.com/r/thomseddon/traefik-forward-auth](https://hub.docker.com/r/thomseddon/traefik-forward-auth)

### Security
- Vault [https://hub.docker.com/_/vault](https://hub.docker.com/_/vault)
- DYNDNS [https://www.cloudflare.com/](https://www.cloudflare.com/)
### IOT
- HomeBridge [https://homebridge.io/](https://homebridge.io/)

### Icons
- Dashboard Icons: [https://github.com/walkxhub/dashboard-icons](https://github.com/walkxhub/dashboard-icons)

### Other
- Habitica: [https://habitica.fandom.com/wiki/Setting_up_Habitica_Locally_on_Docker](https://habitica.fandom.com/wiki/Setting_up_Habitica_Locally_on_Docker)

## Links to check
- Homelab setup: [https://github.com/alphacodinghub/homelab-traefikv2](https://github.com/alphacodinghub/homelab-traefikv2)
- Docker Notify: [https://docker-notify.com/](https://docker-notify.com/) 
- GRAV [https://getgrav.org/](https://getgrav.org/)
