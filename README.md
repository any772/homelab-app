# Homelab-apps
1. Git clone this repo.
2. To run it for the first time just execute ./setup, that bash script is going to prepare everything for a clean setup.
3. If you want to run it as stack in Portainer, then just delete the docker-compose part.
4. Run the setup, and deploy the compose.yml.
5. You should be able to enter the NPM service through web and configure yourself from there.

Service list:
 - Nginx Proxy Manager (jc21/nginx-proxy-manager)
 - Filebrowser (filebrowser/filebrowser)
 - Glance (glanceapp/glance)
 - Jellyfin (jellyfin/jellyfin)
 - Pi-hole (pihole/pihole)

All the images used is from official source, if you want to you could change the images to lscr.io/linuxserver/... or something else

Image sources:
 - https://hub.docker.com/r/jc21/nginx-proxy-manager
 - https://hub.docker.com/r/filebrowser/filebrowser
 - https://hub.docker.com/r/glanceapp/glance
 - https://hub.docker.com/r/jellyfin/jellyfin
 - https://hub.docker.com/r/pihole/pihole
