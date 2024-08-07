# Pi-hole + Unbound for Docker

Easy quick start template to use Pi-hole + Unbound on your local Docker install. I did this to learn more about the two before setting them up on my own Ubuntu server.

## 🚀 Quick Start

1. Make sure you have Docker installed
2. Clone the directory and change into project directory

```sh
$ git clone https://github.com/redoral/pihole-unbound-docker
$ cd pihole-unbound-docker
```

3. Create a `.env` file at the root of the project, then add your desired web password. This will be used to access the pi-hole web GUI.

```js
# .env
WEB_PASSWORD=REPLACE_WITH_DESIRED_PASSWORD
```

4. Run `docker compose`

```sh
$ docker compose up -d
```

5. Verify you can access the pi-hole web GUI by navigating to `localhost/admin` in your browser.

6. Update DNS servers on your devices to use Pi-hole

## ✅ Recommended Adlists

- https://github.com/hagezi/dns-blocklists (I use MultiPRO)
- https://oisd.nl/setup/pihole

## 📕 Resources

- https://github.com/pi-hole/docker-pi-hole
- https://github.com/MatthewVance/unbound-docker
- https://www.youtube.com/watch?v=Y3nm519xHfw
