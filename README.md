# ansible-role-evebox-server

## Configuration

See defaults/main.yml

## Example playbook

```
---

- hosts: evebox_server
  gather_facts: true
  roles:
    - { role: evebox_server, become: yes }
```
