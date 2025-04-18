# Kanola Plasma Image

Containerfile for building Kanola, an unofficial Vanilla OS Plasma image.

This image is based on top of [`kanola-images/base`](https://github.com/Kanola-Images/Base-Image/pkgs/container/base) and offers the default
Unofficial Vanilla OS Desktop Experience with Plasma.

## Create a new Installation with this image

see [here](https://kanola.mmacneill.net/assets/kanola/install.html).

## Build

```bash
vib build recipe.yml
podman image build -t kanola-images/plasma .
```
