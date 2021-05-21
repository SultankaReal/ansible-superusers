# Цель: написать Ansible-playbook, создающий группу пользователей superusers, куда входят пользователи user2 и user3, и которая, выполнив sudo -i, сможет повысить свои полномочия и стать root-пользователем.

## Создан playbook в /etc/ansible/playbooks/superuser.yml (superuser.yml в проекте)

# Применение:
ansible-playbook /etc/ansible/playbooks/superuser.yml
