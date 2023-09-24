# my-homelab-setup
picture of the setup: \
![alt text](https://github.com/N42950M/my-homelab-setup/blob/main/images/dalab.png?raw=true)
### parts from top to bottom:
random monitor from my basement (no idea the model) \
Sophos SG 230 Rev.1 running OPNsense (https://opnsense.org/) \
SODOLA 16 Port Gigabit Ethernet Network Switch \
C2G Legrand 16 Port Patch Panel with VCE CAT6 RJ45 Keystone Couplers \
Dell PowerEdge R430 4B LFF 2x 2.20GHz E5-2630 v4 with 4x WD 14TB Elements Desktop External Hard Drive taken out of the cases \
running https://github.com/openmediavault/openmediavault at the moment, however will be swapped to proxmox when another server is aquired (not enough space on drives to swap currently) \
Asus chromebox flashed to debian with a 12tb wd red pro connected through an external hdd case \
startech.com 1u server rack shelf \
startech.com 16 outlet horizontal 1u \
CyberPower CP1500PFCRM2U UPS \
all on a StarTech.com 12U 19" Rack

### Services being hosted in no particular order, almost everything is in a docker container:
portainer (docker management): https://www.portainer.io/ \
homepage (hompage app dashboard): https://github.com/benphelps/homepage \
mumble (voip server): https://github.com/mumble-voip/mumble-docker \
screego (screen sharing): https://github.com/screego/server \
filebrowser (file browsing): https://github.com/filebrowser/filebrowser \
freshRSS (rss feed reeder): https://github.com/FreshRSS/FreshRSS \
thelounge (IRC client): https://github.com/thelounge/thelounge \
joplin (notes software): https://github.com/laurent22/joplin \
n.eko (docker virtual browser): https://github.com/m1k1o/neko \
tubearchivist (youtube archiver): https://github.com/tubearchivist/tubearchivist \
cyberChef (cyber swiss army knife): https://github.com/gchq/CyberChef \
serge (selfhosted LLMs): https://github.com/serge-chat/serge \
navidrome (music server for my CDs): https://github.com/navidrome/navidrome \
speedtest tracker (hourly speedtest with ookala): https://github.com/henrywhitaker3/Speedtest-Tracker \
jellyfin (media server for my Blurays/DVDs): https://github.com/jellyfin/jellyfin \
nginx proxy manager (reverse proxy): https://github.com/NginxProxyManager/nginx-proxy-manager \
pi-hole (local dns server): https://github.com/pi-hole/pi-hole \
gotify (notification reciever): https://github.com/gotify/server \
diun (docker update notifier): https://github.com/crazy-max/diun \
duckdns (dynamic dns service): https://www.duckdns.org/ \
wg-easy (easy wireguard vpn setup for server): https://github.com/wg-easy/wg-easy \
nginx (hosting simple webpage): https://github.com/nginx/nginx \
minecraft server (self explanatory): https://github.com/itzg/docker-minecraft-server \
HKMP server (hollow knight multiplayer): https://github.com/Extremelyd1/HKMP \
Rdesktop ("vm" connectable through rdp): https://github.com/linuxserver/docker-rdesktop \
vaultwarden (bitwarden server): https://github.com/dani-garcia/vaultwarden \
syncplay server (sync video with others): https://github.com/Syncplay/syncplay