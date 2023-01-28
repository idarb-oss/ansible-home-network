# Ansible Home Network

Ansible home network configuration with `docker`, `pi-hole` and `smallstep` for PKI.

## Configuration

Use the `example.inventory.ini` to create your own `inventory.ini` file for the systems to be setup. And copy the configuration files from `config/templates` to `config/` and edit your changes.

## Run Ansible

```sh
ansible-playbook bootstrap.yaml
```
