# Ansible
## Generando keys ssh
$ ssh-keygen

$ ssh-copy-id user@server

## Agregar agentes registrados
En /etc/ansible/host

server ansible_ssh_user=user

## Ejecución de PLAYBOOKS
### Testeo de sintaxis
ansible-playbook --syntax-check playbook.yml
### Simulación PLAYBOOK
ansible-playbook -C playbook.yml
