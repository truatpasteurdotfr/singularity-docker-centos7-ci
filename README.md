# building a centos7 singularity and docker image for CI

Tru <tru@pasteur.fr>

## Why ?
- initial docker image project https://github.com/truatpasteurdotfr/docker-c7-ci
- adding support for singularity format to be used directly

## Usage
- Docker
```
docker pull ghcr.io/truatpasteurdotfr/singularity-docker-centos7-ci:main
```

- Singularity
```
singularity run oras://ghcr.io/truatpasteurdotfr/singularity-docker-centos7-ci:latest
```