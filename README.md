![haku](img/haku-cloud.gif)

# Nimbus

Nimbus uses a dedicated Raspberry Pi 4 (Model B, 8gb) to manage digital media and self host various projects. It's a solid way to try out new software/tech and I'll take any excuse to work in Linux. 

## Why Pi?

I had an extra one laying around, so it was basically free. That's how money works, right?

I've added a mechanical hard drive to offload write operations and decrease wear & tear on the SD card that serves as the Pi's primary storage. It's encased in aluminum with a pretty strong fan, so noise and heat are minimal. Power consumption is minimal.

For now, the Raspberry Pi is suitable for my household needs and it's weirdly fun to work within the constraints of a single-board computer. I'm certainly keeping an eye on Mini PC deals and eBay listings, though. 

## Current Services

### Household

- Homepage
- Home Assistant

### Media

- Jellyfin
- Kavita

## Docker

Dockerfiles are intentionally separated out into separate directories within [cumulus-services](cumulus-services) to keep things clean, modular, & scalable. 
