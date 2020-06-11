# Ansible role: `docker_base`

Manage Docker installation.

## Tags

| Tag      | Description                                                   |
|----------|---------------------------------------------------------------|
| `setup`  | Install Docker, Docker Compose and Python bindings for Docker |
| `remove` | Remove Docker, Docker Compose and Python bindings for Docker  |

## Variables

See `defaults/main.yml` for the full list of variables.

| Variable                      | Type     | Required | Defaut   | Description            |
|-------------------------------|----------|----------|----------|------------------------|
| `docker_base_compose_version` | `string` | No       | `1.24.1` | Docker Compose version |


## Tasks

```text
main.yml
|
| ------------------------ tags: setup, remove --
|
\__ linux_ubuntu.yml
```
