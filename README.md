# HPD - Ansible - Wordpress - v2

Consiste em um Playbook para criação de um ambiente Wordpress, utilizando Apache + PHP + MySQL.

## How-to Run

Realize os ajustes necessários em:

*hosts*: arquivo de inventário, onde devem constar os IPs das suas máquinas envolvidas

*group_vars/all*: variáveis utilizadas para criação do ambiente

```
ansible-playbook -i hosts playbook.yml
```

