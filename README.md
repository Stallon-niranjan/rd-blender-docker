<div align="center">
  <h1>Blender in Docker</h1>
  <img width="500" src="./cover.png" />
  <p>A collection of Docker containers for running Blender headless or distributed ✨</p>
  <img alt="Python version" src="https://img.shields.io/badge/python-3.6-blue.svg" />
  <img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-yellow.svg" />
  <a href="https://travis-ci.org/nytimes/rd-blender-docker"><img alt="Build status" src="https://travis-ci.org/nytimes/rd-blender-docker.svg?branch=master"></a><br/>
  •
    <a href="https://github.com/nytimes/rd-blender-docker/wiki">Wiki</a> 📝
    •
    <a href="#docker-tags">Docker tags</a> 🏷️
    •
    <a href="#contributing">Contributing</a> 🛠
    •
    <a href="https://hub.docker.com/r/nytimes/blender">Docker Hub</a> 🐋
</div>

## Getting started
The images in this repository are autogenerated by running the `generate.py` script. The script uses `manifest.json` image definitions to define different versions and capabilities. To quickly get started with using the images head over to our [wiki page](https://github.com/nytimes/rd-blender-docker/wiki).

## Docker tags
- `nytimes/blender:latest` - Latest GPU image with latest Blender version
### 2.93
- `nytimes/blender:2.93-cpu-ubuntu18.04`
- `nytimes/blender:2.93-gpu-ubuntu18.04`
### 2.92
- `nytimes/blender:2.92-cpu-ubuntu18.04`
- `nytimes/blender:2.92-gpu-ubuntu18.04`
### 2.91
- `nytimes/blender:2.91-cpu-ubuntu18.04`
- `nytimes/blender:2.91-gpu-ubuntu18.04`
### 2.90
- `nytimes/blender:2.90-cpu-ubuntu18.04`
- `nytimes/blender:2.90-gpu-ubuntu18.04`
### 2.83
- `nytimes/blender:2.83-cpu-ubuntu18.04`
- `nytimes/blender:2.83-gpu-ubuntu18.04`
### 2.82
- `nytimes/blender:2.82-cpu-ubuntu18.04`
- `nytimes/blender:2.82-gpu-ubuntu18.04`
### 2.81
- `nytimes/blender:2.81-cpu-ubuntu18.04`
- `nytimes/blender:2.81-gpu-ubuntu18.04`
### 2.80:
- `nytimes/blender:2.80-cpu-ubuntu18.04`
- `nytimes/blender:2.80-gpu-ubuntu18.04`

## Contributing
To contribute a new image make sure you:
- Add the image definition in the `manifest.json`
- Add the image to this README in the [Docker tags](#docker-tags) section
- PR your change and if the change is approved, we will deploy it Docker Hub

> This repository is maintained by the Research & Development team at The New York Times and is provided as-is for your own use. For more information about R&D at the Times visit [rd.nytimes.com](https://rd.nytimes.com)
