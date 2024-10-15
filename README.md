# Arrows deploy

## Deploy remotely using Ansible

Requirements:

- Ansible installed on your local machine
- SSH access to the remote machine
- Docker installed on the remote machine

Dry run:

```shell
ansible-playbook -i inventory deploy.yml --check
```

Run:

```shell
ansible-playbook -i inventory deploy.yml
```
