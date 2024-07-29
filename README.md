![haku](img/haku-cloud.gif)

# Nimbus

Nimbus uses a dedicated Raspberry Pi 4 (Model B, 8gb) to manage digital media and self host various projects. It's a solid way to try out new software/tech and I'll take any excuse to work in Linux. 

## Why Pi?

I had an extra one laying around, so it was basically free. That's how money works, right?

I've added a mechanical hard drive to offload write operations and decrease wear & tear on the SD card that serves as the Pi's primary storage. It's encased in aluminum with a pretty strong fan, so noise and heat aren't an issue. Power consumption is minimal.

For now, the Raspberry Pi is suitable for my household needs and it's weirdly fun to work within the constraints of a single-board computer. I'm certainly keeping an eye on Mini PC deals and eBay listings, though.

## Services

### Household

- [Homepage](https://gethomepage.dev/latest/)
- [Firefly](https://docs.firefly-iii.org/how-to/)

### Media

- [Jellyfin](https://wiki.kavitareader.com/guides)
- [Kavita](https://jellyfin.org/docs/)
- [FreshRSS](https://github.com/FreshRSS/FreshRSS/tree/edge/Docker#docker-compose-with-postgresql)

### Utilities

- [IT Tools](https://github.com/CorentinTh/it-tools)
- [PicoShare](https://github.com/mtlynch/picoshare)
  
## Future

[Excellent list](https://github.com/awesome-selfhosted/awesome-selfhosted) to browse when scheming about what's next.

### Watching

- [2FAuth](https://docs.2fauth.app/)
- [RPI-Monitor](https://github.com/XavierBerger/RPi-Monitor)
- [Shlink](https://github.com/shlinkio/shlink)
- [WireGuard](https://github.com/mikeroyal/WireGuard-Guide#getting-started-with-wireguard)
- [AdGuard](https://github.com/AdguardTeam/AdGuardHome)
- [Grafana](https://grafana.com/get/?tab=self-managed)
- [Prometheus](https://github.com/prometheus/prometheus)
- [NextCloud](https://nextcloud.com/athome/)
- [Syncthing](https://syncthing.net/)
- [Bitwarden](https://bitwarden.com/help/self-host-an-organization/)
- [Paperless-ngx](https://docs.paperless-ngx.com/)
- [n8n](https://docs.n8n.io/hosting/#)
- [Erpnext](https://erpnext.com/)
- [Wallabag](https://wallabag.org/)
- [Speedtest Tracker](https://github.com/alexjustesen/speedtest-tracker)
- [Umami](https://eu.umami.is/share/LGazGOecbDtaIwDr/umami.is)
- [Mailcow](https://docs.mailcow.email/getstarted/install/)
- [Super Productivity](https://github.com/johannesjo/super-productivity)
  

### On hold

- Home Assistant
- Minecraft 

 
## Docker

Dockerfiles are intentionally separated out into separate directories within [cumulus-services](cumulus-services) to keep things clean, modular, & scalable. 
