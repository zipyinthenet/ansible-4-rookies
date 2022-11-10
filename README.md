# Ansible Playbooks Examples

[Ansible for begginers](https://zipyinthenet.github.io/posts/ansible-for-begginers.html)

## Comprobar con modulo ping:

```bash
ansible target1 -m ping -i inventory.txt
```

## Lanzar playbooks

```bash
ansible-playbooks playbookFile -i inventory.txt
``