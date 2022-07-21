# Dockerfiles

This repository meant to manage my docker deployment container used for personal project or supporting work duties.

| Service Name | Image Tag | Registry | Remarks |
| ------------ | --------- | -------- | ----------- |
| PostgreSQL   | `13.7`    | [Docker Hub](https://hub.docker.com/_/postgres) |             |
| Redis | `7.0.4` | [Docker Hub](https://hub.docker.com/_/redis) | |
| MySQL | `8.0.29` | [Docker Hub](https://hub.docker.com/_/mysql) | |
| n8n | `latest` | [Docker Hub](https://hub.docker.com/r/n8nio/n8n) | Workflow automation tool |

## Prerequisite
1. Install Docker from [here](https://docs.docker.com/desktop/install/linux-install/)
2. Run `docker create network coco-net` to create a network that widely used in this repository.

## External Links
1. [Composerize](https://www.composerize.com/) is a tool to convert `docker run` command to `docker-compose.yml`