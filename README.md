# Ansible role for Rocket.Chat

This role installs [Rocket.Chat](https://rocket.chat/) on a Debian host via Docker. Check [defaults/main.yml](./defaults/main.yml) for configuration options.

## Prerequisites

- Nginx for reverse proxy (can be on the same or different host)
- Letsencrypt
- Docker (installed via galaxy dependency [ansible-role-docker](https://github.com/technischerpunkt/ansible-role-docker))
