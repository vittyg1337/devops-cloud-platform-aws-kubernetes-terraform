# Application Code

## Overview

This folder contains application code used by the DevOps platform.

## Applications

| App | Description |
| --- | --- |
| `docker-webapp/` | Simple Dockerized web application imported from the Docker WebApp project. |

## Current Use

The Docker CI workflow at `.github/workflows/docker-webapp.yml` builds the `docker-webapp` image from this folder.
