# Docker Web App

## Overview

Simple static web application served from an Nginx container.

## Technologies

- Docker
- Nginx

## Features

- Containerized deployment
- Network port mapping
- Lightweight static web server
- GitHub Actions Docker build validation

## Local Build

```powershell
docker build -t docker-webapp ./app/docker-webapp
```

## Local Run

```powershell
docker run --rm -p 8080:80 docker-webapp
```

Open:

```text
http://localhost:8080
```
