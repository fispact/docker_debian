# Debian Docker Container for FISPACT-II
[![](https://img.shields.io/docker/pulls/fispact/debian.svg?style=flat)](https://hub.docker.com/r/fispact/debian) [![](https://img.shields.io/docker/build/fispact/debian.svg?style=flat)](https://hub.docker.com/r/fispact/debian) [![](https://images.microbadger.com/badges/license/fispact/debian.svg)](https://microbadger.com/images/fispact/debian)

This repository contains automated builds of Debian images with the dependencies for [FISPACT-II](http://fispact.ukaea.uk).

For a complete list of Docker images for FISPACT-II, see the [FISPACT-II wiki](https://fispact.ukaea.uk/wiki/Docker_images).

Available on the Docker Hub as [fispact/debian](https://hub.docker.com/r/fispact/debian/).

### Images
The following images are included in this repository, tagged by their operating system version, compiler version and (for some systems) whether or not they include compressed nuclear data libraries for FISPACT-II:
- [![](https://images.microbadger.com/badges/image/fispact/debian:9_gfortran_7.svg)](https://microbadger.com/images/fispact/debian:9_gfortran_7) `9`, `gfortran-7`, [Dockerfile: *fispact/debian:9_gfortran_7*](https://github.com/fispact/docker_debian/blob/9_gfortran_7/Dockerfile)
- [![](https://images.microbadger.com/badges/image/fispact/debian:9_gfortran_7_data.svg)](https://microbadger.com/images/fispact/debian:9_gfortran_7_data) `9`, `gfortran-7`, `data`
