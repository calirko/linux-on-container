# Linux desktop in a container

Lightweight XFCE desktop in the browser, using `linuxserver/webtop:alpine-xfce`.

1. Copy `.env.example` to `.env` and set `DESKTOP_PASSWORD`.
2. `docker compose up -d`
3. Open `http://<ip>:3000` and log in.

On Dokploy: create a Compose service from this repo and set the variables in the Environment tab.
