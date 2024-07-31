# Ansible Fuckiung Hell repro

## playbook_vars_root = top (default)

```bash
ansible-playbook -i inventories/local/ ./play.yml -t xxx
```

## `= all`

then change to `playbook_vars_root = all` in `ansible.cfg` and retry
