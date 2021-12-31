# Docker container management with Traefik v2 and Portainer

A configuration set-up for a Traefik v2 reverse proxy along with Portainer and Docker Compose.

This set-up makes container management & deployment a breeze and the reverse proxy allows for running multiple applications on one Docker host. Traefik will route all the incoming traffic to the appropriate docker containers and through the open-source app Portainer you can speed up software deployments, troubleshoot problems and simplify migrations.

Detailed explanation how to use this in my blog post:
[Docker container management with Traefik v2 and Portainer](https://rafrasenberg.com/posts/docker-container-management-with-traefik-v2-and-portainer/)

## How to run it?

```
$ git clone https://github.com/rafrasenberg/docker-traefik-portainer ./src
$ cd src/core
$ docker-compose up -d
```

For each docker service that is accessible from the internet and from local net set up an DNS entry in [pihole](https://192.168.179.13/admin).

## DNS configuration

Main domain: ululuu.de
CNAME: ycssj0aar5m3grw9.myfritz.net

## Services

### Mailcow

(https://mail-local.ululuu.de)
(https://imap.ululuu.de)
(https://imap-local.ululuu.de)
(https://webmail.ululuu.de)
(https://webmail-local.ululuu.de)
(https://pop3.ululuu.de)
(https://smtp.ululuu.de)
(https://smtp-local.ululuu.de)

### Portainer

(https://portainer.ululuu.de)

### Homer

(https://homer.ululuu.de)

### Traefik

(https://traefik.ululuu.de)

### Jupyter Lab

(https://nb.ululuu.de)

### PiHole

(https://pihole.ululuu.de)

### Internet Speedtest

(https://speedtest.ululuu.de)

### Test server

(https://whoami.ululuu.de)
(https://edge.ululuu.de)
(https://fernzugang.ululuu.de)
(https://lims.ululuu.de)
(https://monitoring.ululuu.de)

### Youtube-Downloader

(https://youtube-dl.ululuu.de)
(https://ytd.ululuu.de)

## Setup Google Oauth Authentification

(https://www.smarthomebeginner.com/google-oauth-with-traefik-2-docker/)

Client ID: 911317711309-pc7elr169qpolko3bpa11fpcnhsn8r7d.apps.googleusercontent.com
Client Secret: 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
