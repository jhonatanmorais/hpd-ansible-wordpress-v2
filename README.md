# HPD - Ansible - Wordpress

Meu primeiro tosco projeto utilizando Ansible.

Consiste em um Playbook para criação de um ambiente Wordpress, utilizando Apache + PHP + MySQL.

## How-to Run

Realize os ajustes necessários em:

*hosts*: arquivo de inventário, onde devem constar os IPs das suas máquinas envolvidas
*roles/db/defaults/main.yml*: variáveis utilizadas na criação do ambiente de DB
*roles/web/defaults/main.yml*: variáveis utilizadas na criação do ambiente Web

```
ansible-playbook -i hosts playbook.yml
```

