# Gitlab-Runner docker compose
## Summary
This is my Gtilab-Runner Docker Compose project.
## Pre-requisites
- `ansible-playbook` commands.
- `docker engine` in target machines.
## Setup
Create a `.env` file where you can configure your environment variables:
```sh
CI_SERVER_URL
REGISTRATION_TOKEN
RUNNER_DESCRIPTION
RUNNER_EXECUTOR
```
## Run
```sh
ansible-playbook -i inventory.yml playbooks.yml
```