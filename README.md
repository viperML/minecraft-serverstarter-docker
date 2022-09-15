# viperML/minecraft-serverstarter-docker

Generic image for serverstarter-based minecraft servers.

## Basic usage

```console
docker run \
    --mount type=bind,source=/path/to/server-setup-config.yaml,destination=/srv/minecraft-vendor/server-setup-config.yaml \
    ghcr.io/viperml/minecraft-serverstarter-docker
```