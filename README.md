# 🗼 The Lookout Config

This is my personal config repo for my own home server lab.

This includes stuff like:

* Wireguard for VPN access
* Jellyfin and the *arr suite for media
* Transmission for torrent downloads
* all based on the linuxserver.io setup mainly.

Check it out and feel free to fork it if you find it useful!

> [!NOTE]
> This assumes you have the following environment variables defined (usually in your `/etc/profile`):
>
> * `LOOKOUT_USER` - Default username for services
> * `LOOKOUT_PASS` - Default password for services
> * `LOOKOUT_DOMAIN` - Domain on which services are running
> * `LOOKOUT_SONARR_API_KEY` - Sonarr API key for services
