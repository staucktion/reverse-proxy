# Reverse Proxy

<h2 id="system-startup">🚀 System Startup</h2>

- Launch reverse proxy by refering [`docker-config`](https://github.com/staucktion/docker-config) repository.

- To generate basic auth password, temporary docker container can be launced.

```
docker run --rm alpine sh -c "apk add --no-cache apache2-utils && htpasswd -nbm admin admin"
```