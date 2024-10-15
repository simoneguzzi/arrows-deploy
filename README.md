# Arrows deploy

## Deploy remotely using Ansible

Requirements:

- Ansible installed on your local machine
- SSH access to the remote machine
- Docker installed on the remote machine
- Knowing the secret 🤫

Dry run:

```shell
ansible-playbook -i inventory --ask-vault-password deploy.yml --check
```

Run:

```shell
ansible-playbook -i inventory --ask-vault-password deploy.yml
```
