# targeting hosts and groups

[hosts and groups](https://docs.ansible.com/ansible/latest/inventory_guide/intro_patterns.html#patterns-targeting-hosts-and-groups)

## Common patterns

- All hosts	-> all (or *)
- One host -> host1
- Multiple hosts -> host1:host2 (or host1,host2)
- One group -> webservers
- Multiple groups -> webservers:dbservers -> all hosts in webservers plus all hosts in dbservers
- Excluding groups -> webservers:!atlanta -> all hosts in webservers except those in atlanta
- Intersection of groups -> webservers:&staging -> any hosts in webservers that are also in staging