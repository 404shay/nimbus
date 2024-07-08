![haku](img/haku-cloud.gif)

# nimbus

I use a dedicated Raspberry Pi to manage my media and self host various projects. It's a solid way to try out new software/tech and I'll take any excuse to use Linux. 

## why pi?
I had an extra one laying around, so it was basically free. That's how money works, right?

Joking aside, it does actually fit my household needs (for now, anyways). I've added a mechanical hard drive to offload write operations and decrease wear & tear on the SD card that serves as the Pi's primary storage. It's encased in aluminum with a pretty strong fan, so noise and heat are minimal. Power consumption is essentially nil. 

It also helps that I use virtual servers for more robust endeavors; [nimbus](https://github.com/404shay/nimbus/tree/main) is not trying to do it all. 

## current services

- Homepage
- Jellyfin
- Kavita
- Home Assistant

## docker

Dockerfiles are intentionally separated out into separate directories within [cumulus-services](cumulus-services) to keep things clean, modular, & scalable. 
