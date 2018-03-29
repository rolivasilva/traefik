# traefik
Configuration traefik







```bash
docker run -d -p 8080:8080 -p 80:80 \
-v $PWD/traefik.toml:/etc/traefik/traefik.toml \
-v /var/run/docker.sock:/var/run/docker.sock \
--name traefik \
traefik
````

- Ejemplo 1

```bash
docker run -d --name test.1 rolivasilva/whoami:1.0
````

- Ejemplo 2

```bash
docker run -d --name test.2 rolivasilva/whoami:1.0
````

- Ejemplo 3

```bash
docker run -d --name test.3 rolivasilva/whoami
````