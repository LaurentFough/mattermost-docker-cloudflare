# Mattermost Docker
The official Docker deployment solution for Mattermost.

## Install & Usage

Refer to the [Mattermost Docker deployment guide](https://docs.mattermost.com/install/install-docker.html) for instructions on how to install and use this Docker image.

### Run with Cloudflare Tunnels
1. Add the Tunnel Token provided by Cloudflare to the variable `CLOUDFLARED_TUNNEL_TOKEN` in the `.env` file.
2. Run `sudo docker compose -f docker-compose.yml -f docker-compose.cft.yml up -d`

## Contribute
PRs are welcome, refer to our [contributing guide](https://developers.mattermost.com/contribute/getting-started/) for an overview of the Mattermost contribution process.

## Upgrading from `mattermost-docker`

This repository replaces the [deprecated mattermost-docker repository](https://github.com/mattermost/mattermost-docker). For an in-depth guide to upgrading, please refer to [this document](https://github.com/mattermost/docker/blob/main/scripts/UPGRADE.md).
